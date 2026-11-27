---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: the business entity described on the Order Form
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export and embargo restrictions
    text: Customer will not permit any Authorized User to access or use the Services (i) if such person is a resident of a country embargoed by the United States
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
name: Haus
provenance_date: '2026-11-09'
provider_name: Haus
provider_slug: haus
slug: haus-eligibility
source_date: '2026-11-09'
source_filename: haus-eligibility.yml
source_heading: Eligibility
source_page: https://www.haus.io/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Haus\naid: haus\nurl: https://www.haus.io/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: the business entity described on the Order Form\nrestricted_uses:\n- summary: Export and embargo restrictions\n  text: Customer will not permit any Authorized User to access or use the Services (i) if such person is a resident\n    of a country embargoed by the United States\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/haus/eligibility/haus-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Haus's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Marketing
- Analytics
- Incrementality
- Measurements
- Attribution
- Media Mix Modeling
- Causal Inference
- Advertising
- MarTech
---
