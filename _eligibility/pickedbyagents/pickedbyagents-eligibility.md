---
api_specs:
- filename: pickedbyagents-research-api-api-openapi.yml
  format: yaml
  label: Picked by Agents Research API
  slug: pickedbyagents-research-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pickedbyagents/openapi/pickedbyagents-research-api-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you use the site for a business, you agree on its behalf.
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
name: Picked by Agents
provenance_date: '2026-11-10'
provider_name: Picked by Agents
provider_slug: pickedbyagents
slug: pickedbyagents-eligibility
source_date: '2026-11-10'
source_filename: pickedbyagents-eligibility.yml
source_heading: Eligibility
source_page: https://pickedbyagents.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Picked by Agents\naid: pickedbyagents\nurl: https://pickedbyagents.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you use the site for a business, you agree on its behalf.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/pickedbyagents/eligibility/pickedbyagents-eligibility.yml
stated_fields:
- entity_types
summary_line: 1 quoted statement, read from Picked by Agents's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Monitoring
- Visibility
- Local Business
---
