---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Be at least 18 years old
    type: individual
  - text: Advisor Pro is a separate workspace for professional travel advisors
    type: other
  minimum_age:
    text: Be at least 18 years old
    value: '18'
  restricted_uses:
  - summary: Tool results not for AI training
    text: Do not use the results to train or improve an AI model
  - summary: No bulk or scheduled tool runs
    text: Do not run the tool in bulk or on a schedule to collect our prices, ranges or sources
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
name: Endless Travel Plans
provenance_date: '2026-11-09'
provider_name: Endless Travel Plans
provider_slug: endlesstravelplans-com
slug: endlesstravelplans-com-eligibility
source_date: '2026-11-09'
source_filename: endlesstravelplans-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.endlesstravelplans.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Endless Travel Plans\naid: endlesstravelplans-com\nurl: https://www.endlesstravelplans.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Be at least 18 years old\n- type: other\n  text: Advisor Pro is a separate workspace for professional travel advisors\nrestricted_uses:\n- summary: Tool results not for AI training\n  text: Do not use the results to train or improve an AI model\n- summary: No bulk or scheduled tool runs\n  text: Do not run the tool in bulk or on a schedule to collect our prices, ranges or sources\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Be at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/endlesstravelplans-com/eligibility/endlesstravelplans-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Endless Travel Plans's own page on 2026-11-09.
synthetic: false
tags:
- Travel
- Family
- Vacation
- Planning
- Tools
- Guides
---
