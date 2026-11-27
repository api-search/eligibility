---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old to create an account or use the Service.
    type: individual
  minimum_age:
    text: You must be at least 18 years old to create an account or use the Service.
    value: '18'
  restricted_uses:
  - summary: Personal non-commercial use only
    text: for your own personal, non-commercial use
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: access is granted in batches at our discretion
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Quantral
provenance_date: '2026-11-10'
provider_name: Quantral
provider_slug: quantral
slug: quantral-eligibility
source_date: '2026-11-10'
source_filename: quantral-eligibility.yml
source_heading: Eligibility
source_page: https://quantral.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Quantral\naid: quantral\nurl: https://quantral.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old to create an account or use the Service.\nrestricted_uses:\n- summary: Personal non-commercial use only\n  text: for your own personal, non-commercial use\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: access is granted in batches at our discretion\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to create an account or use the Service.\n"
source_yaml_url: https://artifacts.apis.io/quantral/eligibility/quantral-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Quantral's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Finance
- Data
- Analytics
- Artificial Intelligence
---
