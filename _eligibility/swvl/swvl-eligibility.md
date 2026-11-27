---
claim_count: 4
description: ''
doc:
  countries:
    excluded:
    - US
    - CN
    served: []
    text: from within any country in the world (excluding the United States and its territories and possessions and Mainland China)
  minimum_age:
    text: You must be at least 18 years of age, or the age of legal majority in your jurisdiction (if different than 18), to set up and maintain an Account.
    value: '18'
  restricted_uses:
  - summary: Lawful purposes only
    text: you may only use the Swvl Services for lawful purposes (e.g., no transport of unlawful or hazardous materials).
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: In certain instances, you may be asked to provide proof of identity to access or use the Swvl Services
excluded_countries:
- US
- CN
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Swvl
provenance_date: '2026-11-10'
provider_name: Swvl
provider_slug: swvl
slug: swvl-eligibility
source_date: '2026-11-10'
source_filename: swvl-eligibility.yml
source_heading: Eligibility
source_page: https://www.swvl.com/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Swvl\naid: swvl\nurl: https://www.swvl.com/terms-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - US\n  - CN\n  text: from within any country in the world (excluding the United States and its territories and possessions and\n    Mainland China)\nentity_types: []\nrestricted_uses:\n- summary: Lawful purposes only\n  text: you may only use the Swvl Services for lawful purposes (e.g., no transport of unlawful or hazardous materials).\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: In certain instances, you may be asked to provide proof of identity to\
  \ access or use the Swvl Services\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years of age, or the age of legal majority in your jurisdiction (if different than\n    18), to set up and maintain an Account.\n"
source_yaml_url: https://artifacts.apis.io/swvl/eligibility/swvl-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Swvl's own page on 2026-11-10.
synthetic: false
tags:
- Mobility
- Transportation
- On-Demand
- Fleet Management
- B2B Solutions
---
