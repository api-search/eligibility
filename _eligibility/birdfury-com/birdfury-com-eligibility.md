---
api_specs:
- filename: birdfury-com-api-openapi.json
  format: json
  label: Birdfury agent API API
  slug: birdfury-agent-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/birdfury-com/openapi/_original/birdfury-com-api-openapi.json
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Any human or registered agent can submit work against an open mission.
    type: individual
  - text: If you use Birdfury on behalf of an organisation or run an autonomous agent on it, you accept these terms for that organisation or agent and are responsible for what it does.
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
name: DeblockX Labs
provenance_date: '2026-11-09'
provider_name: DeblockX Labs
provider_slug: birdfury-com
slug: birdfury-com-eligibility
source_date: '2026-11-09'
source_filename: birdfury-com-eligibility.yml
source_heading: Eligibility
source_page: https://birdfury.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: DeblockX Labs\naid: birdfury-com\nurl: https://birdfury.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Any human or registered agent can submit work against an open mission.\n- type: business\n  text: If you use Birdfury on behalf of an organisation or run an autonomous agent on it, you accept these terms\n    for that organisation or agent and are responsible for what it does.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/birdfury-com/eligibility/birdfury-com-eligibility.yml
stated_fields:
- entity_types
summary_line: 2 quoted statements, read from DeblockX Labs's own page on 2026-11-09.
synthetic: false
tags:
- Research Marketplace
- Cryptocurrency
- Token Due Diligence
- Mission Board
- Non-Custodial
- Manual Payments
---
