---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: This website (Site) is provided for personal, non-commercial transitory viewing only.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Commercial use restricted
    text: sell any information herein or use it for commercial purposes;
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
name: Empower
provenance_date: '2026-11-09'
provider_name: Empower
provider_slug: empower
slug: empower-eligibility
source_date: '2026-11-09'
source_filename: empower-eligibility.yml
source_heading: Eligibility
source_page: https://www.empower.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Empower\naid: empower\nurl: https://www.empower.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: This website (Site) is provided for personal, non-commercial transitory viewing only.\nrestricted_uses:\n- summary: Commercial use restricted\n  text: sell any information herein or use it for commercial purposes;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/empower/eligibility/empower-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Empower's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Finance
- Investment
- Retirement
- Financial-Tools
---
