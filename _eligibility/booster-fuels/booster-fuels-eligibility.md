---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Services are only available in the United States.
  entity_types:
  - text: You must be at least 18 years of age, or the age of legal majority in your jurisdiction (if different than 18), to obtain an Account.
    type: individual
  minimum_age:
    text: You must be at least 18 years of age, or the age of legal majority in your jurisdiction (if different than 18), to obtain an Account.
    value: '18'
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: In certain instances, you may be asked to provide proof of identity to access or use the Services
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Booster Fuels
provenance_date: '2026-11-09'
provider_name: Booster Fuels
provider_slug: booster-fuels
slug: booster-fuels-eligibility
source_date: '2026-11-09'
source_filename: booster-fuels-eligibility.yml
source_heading: Eligibility
source_page: https://boosterusa.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Booster Fuels\naid: booster-fuels\nurl: https://boosterusa.com/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Services are only available in the United States.\nentity_types:\n- type: individual\n  text: You must be at least 18 years of age, or the age of legal majority in your jurisdiction (if different than\n    18), to obtain an Account.\nrestricted_uses: []\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: In certain instances, you may be asked to provide proof of identity to access or use the Services\nminimum_age:\n  value:\
  \ '18'\n  text: You must be at least 18 years of age, or the age of legal majority in your jurisdiction (if different than\n    18), to obtain an Account.\n"
source_yaml_url: https://artifacts.apis.io/booster-fuels/eligibility/booster-fuels-eligibility.yml
stated_fields:
- countries
- entity_types
- verification
- minimum_age
summary_line: 4 quoted statements, read from Booster Fuels's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Energy
- Fuel Delivery
- Fleet Management
- Mobile Fueling
- Logistics
- Transportation
- Sustainability
---
