---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Services are intended solely for personal, non-commercial use.
    type: individual
  minimum_age:
    text: The User confirms that they are at least 18 years old and legally capable of entering into this agreement.
    value: '18'
  restricted_uses:
  - summary: Non-commercial use only
    text: The Services are intended solely for personal, non-commercial use.
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
name: Bilance
provenance_date: '2026-11-09'
provider_name: Bilance
provider_slug: bilanceapp-com
slug: bilanceapp-com-eligibility
source_date: '2026-11-09'
source_filename: bilanceapp-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.bilanceapp.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bilance\naid: bilanceapp-com\nurl: https://www.bilanceapp.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Services are intended solely for personal, non-commercial use.\nrestricted_uses:\n- summary: Non-commercial use only\n  text: The Services are intended solely for personal, non-commercial use.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The User confirms that they are at least 18 years old and legally capable of entering into this agreement.\n"
source_yaml_url: https://artifacts.apis.io/bilanceapp-com/eligibility/bilanceapp-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Bilance's own page on 2026-11-09.
synthetic: false
tags:
- Finance
- Budgeting
- Banking
- Personal Finance
- Mobile App
---
