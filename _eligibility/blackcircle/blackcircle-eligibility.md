---
claim_count: 6
description: ''
doc:
  countries:
    excluded:
    - GB
    - US
    - HK
    - AE
    served: []
    text: This Website is not directed at persons in the United Kingdom, the United States, Hong Kong or the United Arab Emirates (outside the ADGM and DIFC), unless a Group entity has confirmed in writing that it may lawfully deal with them.
  entity_types:
  - text: Investment-related information on this Website is intended solely for professional, institutional, sophisticated or other eligible investors, as applicable under the laws and regulations of their respective jurisdictions.
    type: other
  - text: If you are acting on behalf of an entity, you confirm that you are authorised to act on its behalf.
    type: business
  minimum_age:
    text: You confirm that you are at least 18 years old and have legal capacity to agree to these Terms.
    value: '18'
  restricted_uses:
  - summary: Not for retail investors
    text: It is not intended for retail investors.
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: Access to any investment, product, structure or service is subject to applicable eligibility requirements, onboarding procedures, AML/KYC and sanctions checks, and the terms of the relevant offering and contractual documentation.
excluded_countries:
- GB
- US
- HK
- AE
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Blackcircle
provenance_date: '2026-11-09'
provider_name: Blackcircle
provider_slug: blackcircle
slug: blackcircle-eligibility
source_date: '2026-11-09'
source_filename: blackcircle-eligibility.yml
source_heading: Eligibility
source_page: https://theblackcircle.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Blackcircle\naid: blackcircle\nurl: https://theblackcircle.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - GB\n  - US\n  - HK\n  - AE\n  text: This Website is not directed at persons in the United Kingdom, the United States, Hong Kong or the United\n    Arab Emirates (outside the ADGM and DIFC), unless a Group entity has confirmed in writing that it may lawfully\n    deal with them.\nentity_types:\n- type: other\n  text: Investment-related information on this Website is intended solely for professional, institutional, sophisticated\n    or other eligible investors, as applicable\
  \ under the laws and regulations of their respective jurisdictions.\n- type: business\n  text: If you are acting on behalf of an entity, you confirm that you are authorised to act on its behalf.\nrestricted_uses:\n- summary: Not for retail investors\n  text: It is not intended for retail investors.\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: Access to any investment, product, structure or service is subject to applicable eligibility requirements,\n    onboarding procedures, AML/KYC and sanctions checks, and the terms of the relevant offering and contractual\n    documentation.\nminimum_age:\n  value: '18'\n  text: You confirm that you are at least 18 years old and have legal capacity to agree to these Terms.\n"
source_yaml_url: https://artifacts.apis.io/blackcircle/eligibility/blackcircle-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Blackcircle's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Wealth Management
- Private Banking
- Investment
- Multi-jurisdictional
---
