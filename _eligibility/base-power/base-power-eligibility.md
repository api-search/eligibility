---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: you must be at least 18 years of age and a resident of an area of the United States where Base plans to provide the Products for installation.
  entity_types:
  - text: To enter into this Agreement and Preorder a Product, you must be at least 18 years of age and a resident of an area of the United States where Base plans to provide the Products for installation.
    type: individual
  minimum_age:
    text: you must be at least 18 years of age
    value: '18'
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
name: Base Power
provenance_date: '2026-11-09'
provider_name: Base Power
provider_slug: base-power
slug: base-power-eligibility
source_date: '2026-11-09'
source_filename: base-power-eligibility.yml
source_heading: Eligibility
source_page: https://www.basepowercompany.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Base Power\naid: base-power\nurl: https://www.basepowercompany.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: you must be at least 18 years of age and a resident of an area of the United States where Base plans to\n    provide the Products for installation.\nentity_types:\n- type: individual\n  text: To enter into this Agreement and Preorder a Product, you must be at least 18 years of age and a resident\n    of an area of the United States where Base plans to provide the Products for installation.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb:\
  \ null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you must be at least 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/base-power/eligibility/base-power-eligibility.yml
stated_fields:
- countries
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from Base Power's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Clean Energy
- Energy
- Home Battery
- Energy Storage
- Electricity
- Grid
- Retail Electric Provider
- Texas
- Illinois
---
