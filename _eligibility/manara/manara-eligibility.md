---
claim_count: 5
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - KP
    served: []
    text: You may not download or use the Service if you are located in a country or region subject to U.S. or E.U. government embargo (including Cuba, Iran, North Korea, and the Crimea region) unless that use is authorized by the United States and other relevant authorities.
  entity_types:
  - text: REFERS TO THE INDIVIDUAL OR LEGAL ENTITY, AS APPLICABLE, IDENTIFIED AS THE USER WHEN YOU REGISTERED FOR THE SERVICES.
    type: business
  minimum_age:
    text: You represent that you are (i) at least eighteen (18) years old
    value: '18'
  restricted_uses:
  - summary: Users under 18 / not able to contract
    text: Use the Service if you are not able to form legally binding contracts (for example, if you are under 18 years old)
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Manara reserves the right, in its sole discretion, to accept or reject user registration to use the Services.
excluded_countries:
- CU
- IR
- KP
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Manara
provenance_date: '2026-11-10'
provider_name: Manara
provider_slug: manara
slug: manara-eligibility
source_date: '2026-11-10'
source_filename: manara-eligibility.yml
source_heading: Eligibility
source_page: https://manara.tech/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Manara\naid: manara\nurl: https://manara.tech/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  text: You may not download or use the Service if you are located in a country or region subject to U.S. or E.U.\n    government embargo (including Cuba, Iran, North Korea, and the Crimea region) unless that use is authorized\n    by the United States and other relevant authorities.\nentity_types:\n- type: business\n  text: REFERS TO THE INDIVIDUAL OR LEGAL ENTITY, AS APPLICABLE, IDENTIFIED AS THE USER WHEN YOU REGISTERED FOR\n    THE SERVICES.\nrestricted_uses:\n- summary:\
  \ Users under 18 / not able to contract\n  text: Use the Service if you are not able to form legally binding contracts (for example, if you are under 18\n    years old)\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Manara reserves the right, in its sole discretion, to accept or reject user registration to use the Services.\nminimum_age:\n  value: '18'\n  text: You represent that you are (i) at least eighteen (18) years old\n"
source_yaml_url: https://artifacts.apis.io/manara/eligibility/manara-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Manara's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Education
- Training
- Upskilling
- Talent
- Workforce Development
- MENA
- Cloud
- Artificial Intelligence
---
