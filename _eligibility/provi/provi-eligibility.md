---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You are located within the Provi Markets or otherwise located in a jurisdiction where your access to our Site is not prohibited
  entity_types:
  - text: IF YOU ARE ENTERING INTO THIS AGREEMENT ON BEHALF OF A COMPANY OR OTHER LEGAL ENTITY, YOUR ACCEPTANCE REPRESENTS THAT YOU ARE 21 YEARS OF AGE OR OLDER
    type: individual
  minimum_age:
    text: You are 21 years of age or older
    value: '21'
  restricted_uses:
  - summary: No personal or household use
    text: (iii) will not use the Site or Services for any personal or household purpose.
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
name: Provi
provenance_date: '2026-11-10'
provider_name: Provi
provider_slug: provi
slug: provi-eligibility
source_date: '2026-11-10'
source_filename: provi-eligibility.yml
source_heading: Eligibility
source_page: https://app.provi.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Provi\naid: provi\nurl: https://app.provi.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: You are located within the Provi Markets or otherwise located in a jurisdiction where your access to our\n    Site is not prohibited\nentity_types:\n- type: individual\n  text: IF YOU ARE ENTERING INTO THIS AGREEMENT ON BEHALF OF A COMPANY OR OTHER LEGAL ENTITY, YOUR ACCEPTANCE REPRESENTS\n    THAT YOU ARE 21 YEARS OF AGE OR OLDER\nrestricted_uses:\n- summary: No personal or household use\n  text: (iii) will not use the Site or Services for any personal or household\
  \ purpose.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '21'\n  text: You are 21 years of age or older\n"
source_yaml_url: https://artifacts.apis.io/provi/eligibility/provi-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Provi's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Beverages
- Alcohol
- Marketplace
- B2B
- E-Commerce
- Distribution
- Hospitality
---
