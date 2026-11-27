---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: We provide Services to businesses only.
    type: business
  minimum_age:
    text: you are at least 18 years old
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
name: Jelly
provenance_date: '2026-11-09'
provider_name: Jelly
provider_slug: jelly
slug: jelly-eligibility
source_date: '2026-11-09'
source_filename: jelly-eligibility.yml
source_heading: Eligibility
source_page: https://www.getjelly.co.uk/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Jelly\naid: jelly\nurl: https://www.getjelly.co.uk/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: We provide Services to businesses only.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you are at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/jelly/eligibility/jelly-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from Jelly's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Hospitality
- Restaurant
- Kitchen Management
- Food Costing
- Recipe Costing
- Invoice Processing
- GraphQL
- Software-as-a-Service
---
