---
api_specs:
- filename: agentdomainsearch-com-api-openapi.json
  format: json
  label: Agent Domain Search Api API
  slug: agent-domain-search-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentdomainsearch-com/openapi/_original/agentdomainsearch-com-api-openapi.json
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: a valid individual name or registered business name is required.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Illegal, abusive or fraudulent purposes
    text: We reserve the right to refuse service or remove domains used for illegal, abusive, or fraudulent purposes.
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
name: Agent Domain Search
provenance_date: '2026-11-09'
provider_name: Agent Domain Search
provider_slug: agentdomainsearch-com
slug: agentdomainsearch-com-eligibility
source_date: '2026-11-09'
source_filename: agentdomainsearch-com-eligibility.yml
source_heading: Eligibility
source_page: https://agentdomainsearch.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Agent Domain Search\naid: agentdomainsearch-com\nurl: https://agentdomainsearch.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: a valid individual name or registered business name is required.\nrestricted_uses:\n- summary: Illegal, abusive or fraudulent purposes\n  text: We reserve the right to refuse service or remove domains used for illegal, abusive, or fraudulent purposes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/agentdomainsearch-com/eligibility/agentdomainsearch-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Agent Domain Search's own page on 2026-11-09.
synthetic: false
tags:
- Domain Registration
- DNS Management
---
