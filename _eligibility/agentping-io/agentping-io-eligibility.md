---
api_specs:
- filename: agentping-io-openapi-generated.yml
  format: yaml
  label: Agent Ping API
  slug: agentping-io-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentping-io/openapi/_ae-authored/agentping-io-openapi-generated.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: By creating an account or sending data to the service, you agree to them on behalf of yourself and any organisation you represent.
    type: business
  minimum_age:
    text: You must be old enough to form a binding contract in your jurisdiction.
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
name: Agent Ping
provenance_date: '2026-11-09'
provider_name: Agent Ping
provider_slug: agentping-io
slug: agentping-io-eligibility
source_date: '2026-11-09'
source_filename: agentping-io-eligibility.yml
source_heading: Eligibility
source_page: https://agentping.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Agent Ping\naid: agentping-io\nurl: https://agentping.io/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: By creating an account or sending data to the service, you agree to them on behalf of yourself and any organisation\n    you represent.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: You must be old enough to form a binding contract in your jurisdiction.\n"
source_yaml_url: https://artifacts.apis.io/agentping-io/eligibility/agentping-io-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from Agent Ping's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Observability
- Monitoring
- Cost Management
- Software-as-a-Service
---
