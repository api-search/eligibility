---
claim_count: 7
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - KP
    - SD
    - SY
    served: []
    text: Use of the Services is prohibited in certain restricted countries and regions, including Cuba, Iran, North Korea, Sudan, Syria, and the Crimea, Donetsk, and Luhansk Regions of Ukraine.
  entity_types:
  - text: You must be at least 18 years old to use the Services.
    type: individual
  - text: If you are using the Services on behalf of a company, organization, or other legal entity, you are binding that company, organization, or other legal entity to these Terms
    type: business
  minimum_age:
    text: You must be at least 18 years old to use the Services.
    value: '18'
  restricted_uses:
  - summary: Commercial use of evaluation software
    text: You shall not distribute the Evaluation Software to any third party or distribute or otherwise use commercially any product of or output from the Evaluation Software.
  - summary: Export control compliance
    text: You agree to comply fully with all United States and foreign export laws and regulations
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Users must register an account to access certain Services. You agree to provide accurate, current, and complete information during the registration process.
excluded_countries:
- CU
- IR
- KP
- SD
- SY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Digimarc
provenance_date: '2026-11-09'
provider_name: Digimarc
provider_slug: digimarc
slug: digimarc-eligibility
source_date: '2026-11-09'
source_filename: digimarc-eligibility.yml
source_heading: Eligibility
source_page: https://www.digimarc.com/products/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Digimarc\naid: digimarc\nurl: https://www.digimarc.com/products/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  - SD\n  - SY\n  text: Use of the Services is prohibited in certain restricted countries and regions, including Cuba, Iran, North\n    Korea, Sudan, Syria, and the Crimea, Donetsk, and Luhansk Regions of Ukraine.\nentity_types:\n- type: individual\n  text: You must be at least 18 years old to use the Services.\n- type: business\n  text: If you are using the Services on behalf of a company, organization, or other legal entity, you are binding\n\
  \    that company, organization, or other legal entity to these Terms\nrestricted_uses:\n- summary: Commercial use of evaluation software\n  text: You shall not distribute the Evaluation Software to any third party or distribute or otherwise use commercially\n    any product of or output from the Evaluation Software.\n- summary: Export control compliance\n  text: You agree to comply fully with all United States and foreign export laws and regulations\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Users must register an account to access certain Services. You agree to provide accurate, current, and complete\n    information during the registration process.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to use the Services.\n"
source_yaml_url: https://artifacts.apis.io/digimarc/eligibility/digimarc-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 7 quoted statements, read from Digimarc's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Digital Watermarking
- Product Authentication
- Anti-Counterfeiting
- Connected Packaging
- QR Codes
- Content Provenance
- Mobile SDK
---
