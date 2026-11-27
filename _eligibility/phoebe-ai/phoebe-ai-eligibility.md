---
api_specs:
- filename: phoebe-ai-openapi-generated.yml
  format: yaml
  label: Phoebe API
  slug: phoebe-ai-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/phoebe-ai/openapi/_ae-authored/phoebe-ai-openapi-generated.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: whether acting as an individual user or on behalf of the company you represent
    type: individual
  - text: on behalf of the company you represent
    type: business
  minimum_age:
    text: null
    value: null
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
name: Phoebe
provenance_date: '2026-11-10'
provider_name: Phoebe
provider_slug: phoebe-ai
slug: phoebe-ai-eligibility
source_date: '2026-11-10'
source_filename: phoebe-ai-eligibility.yml
source_heading: Eligibility
source_page: https://withcoral.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Phoebe\naid: phoebe-ai\nurl: https://withcoral.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: whether acting as an individual user or on behalf of the company you represent\n- type: business\n  text: on behalf of the company you represent\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/phoebe-ai/eligibility/phoebe-ai-eligibility.yml
stated_fields:
- entity_types
summary_line: 2 quoted statements, read from Phoebe's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- Machine Learning
- Platform
- Ethics
- Enterprise
---
