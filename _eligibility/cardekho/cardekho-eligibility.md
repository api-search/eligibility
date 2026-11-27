---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Service available through or use of the Website is available only to persons of majority (18 years of age or more)
    type: individual
  minimum_age:
    text: persons of majority (18 years of age or more)
    value: '18'
  restricted_uses:
  - summary: Used car purchases limited to individuals
    text: Only individuals are permitted to purchase any used cars listed for sale on Website
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
name: Cardekho
provenance_date: '2026-11-09'
provider_name: Cardekho
provider_slug: cardekho
slug: cardekho-eligibility
source_date: '2026-11-09'
source_filename: cardekho-eligibility.yml
source_heading: Eligibility
source_page: https://www.cardekho.com/info/terms_and_condition
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cardekho\naid: cardekho\nurl: https://www.cardekho.com/info/terms_and_condition\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Service available through or use of the Website is available only to persons of majority (18 years of age\n    or more)\nrestricted_uses:\n- summary: Used car purchases limited to individuals\n  text: Only individuals are permitted to purchase any used cars listed for sale on Website\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value:\
  \ '18'\n  text: persons of majority (18 years of age or more)\n"
source_yaml_url: https://artifacts.apis.io/cardekho/eligibility/cardekho-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Cardekho's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Automotive
- Marketplace
- India
- CarTech
---
