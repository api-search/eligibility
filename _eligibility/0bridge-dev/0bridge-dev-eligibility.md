---
api_specs:
- filename: 0bridge-dev-openapi-generated.yml
  format: yaml
  label: 0bridge API
  slug: 0bridge-dev-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/0bridge-dev/openapi/_ae-authored/0bridge-dev-openapi-generated.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you use 0 bridge for an organization, you accept these terms for that organization.
    type: business
  - text: If you buy as a consumer (for example in the EU, the UK or Korea), you can withdraw within 14 days of your first payment for a subscription and get a full refund
    type: individual
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
name: 0bridge
provenance_date: '2026-11-09'
provider_name: 0bridge
provider_slug: 0bridge-dev
slug: 0bridge-dev-eligibility
source_date: '2026-11-09'
source_filename: 0bridge-dev-eligibility.yml
source_heading: Eligibility
source_page: https://0bridge.dev/policy/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: 0bridge\naid: 0bridge-dev\nurl: https://0bridge.dev/policy/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you use 0 bridge for an organization, you accept these terms for that organization.\n- type: individual\n  text: If you buy as a consumer (for example in the EU, the UK or Korea), you can withdraw within 14 days of your\n    first payment for a subscription and get a full refund\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/0bridge-dev/eligibility/0bridge-dev-eligibility.yml
stated_fields:
- entity_types
summary_line: 2 quoted statements, read from 0bridge's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- MCP
- Integration
- Team Collaboration
- Productivity
---
