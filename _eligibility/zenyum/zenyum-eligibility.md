---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - SG
    text: This Website is intended for users located in Singapore.
  entity_types:
  - text: you are at least 18 years of age, or the age that the law in the country you reside in requires
    type: individual
  minimum_age:
    text: you are at least 18 years of age, or the age that the law in the country you reside in requires for you to legally access or use the Services, whichever is higher
    value: '18'
  restricted_uses:
  - summary: Illegal or harmful use
    text: use the Services for any illegal, offensive, immoral or unethical purpose.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Zenyum
provenance_date: '2026-11-10'
provider_name: Zenyum
provider_slug: zenyum
slug: zenyum-eligibility
source_date: '2026-11-10'
source_filename: zenyum-eligibility.yml
source_heading: Eligibility
source_page: https://www.zenyum.com/sg-en/website-terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Zenyum\naid: zenyum\nurl: https://www.zenyum.com/sg-en/website-terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - SG\n  excluded: []\n  text: This Website is intended for users located in Singapore.\nentity_types:\n- type: individual\n  text: you are at least 18 years of age, or the age that the law in the country you reside in requires\nrestricted_uses:\n- summary: Illegal or harmful use\n  text: use the Services for any illegal, offensive, immoral or unethical purpose.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text:\
  \ you are at least 18 years of age, or the age that the law in the country you reside in requires for you\n    to legally access or use the Services, whichever is higher\n"
source_yaml_url: https://artifacts.apis.io/zenyum/eligibility/zenyum-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Zenyum's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- Dental
- Oral Care
- Clear Aligners
- Consumer Health
- E-Commerce
- Direct to Consumer
- Singapore
---
