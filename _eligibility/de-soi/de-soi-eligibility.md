---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least the age of majority in your state of residence to purchase products through our Services.
    type: individual
  minimum_age:
    text: You must be at least the age of majority in your state of residence to purchase products through our Services. Minors may use the Services only with the involvement and consent of a parent or legal guardian.
    value: age of majority in state of residence
  restricted_uses:
  - summary: Resale of products
    text: Resell De Soi products without our prior written permission.
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
name: De Soi
provenance_date: '2026-11-09'
provider_name: De Soi
provider_slug: de-soi
slug: de-soi-eligibility
source_date: '2026-11-09'
source_filename: de-soi-eligibility.yml
source_heading: Eligibility
source_page: https://drinkdesoi.com/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: De Soi\naid: de-soi\nurl: https://drinkdesoi.com/policies/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least the age of majority in your state of residence to purchase products through our Services.\nrestricted_uses:\n- summary: Resale of products\n  text: Resell De Soi products without our prior written permission.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: age of majority in state of residence\n  text: You must be at least the age of\
  \ majority in your state of residence to purchase products through our Services.\n    Minors may use the Services only with the involvement and consent of a parent or legal guardian.\n"
source_yaml_url: https://artifacts.apis.io/de-soi/eligibility/de-soi-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from De Soi's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Beverages
- Non-Alcoholic
- Startups
- Los Angeles
---
