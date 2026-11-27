---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Uses that could cause legal liability
    text: if the Company ascertain, at its sole discretion, that your actions may cause legal liability for you, the Company, other users, or third parties.
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
name: Understory
provenance_date: '2026-11-10'
provider_name: Understory
provider_slug: understory
slug: understory-eligibility
source_date: '2026-11-10'
source_filename: understory-eligibility.yml
source_heading: Eligibility
source_page: https://understoryweather.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Understory\naid: understory\nurl: https://understoryweather.com/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Uses that could cause legal liability\n  text: if the Company ascertain, at its sole discretion, that your actions may cause legal liability for you, the\n    Company, other users, or third parties.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/understory/eligibility/understory-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Understory's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Climate
- Insurance
- Insurtech
- Weather
- Parametric Insurance
- Sensors
---
