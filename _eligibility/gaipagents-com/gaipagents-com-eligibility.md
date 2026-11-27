---
api_specs:
- filename: gaipagents-com-agent-observatory-api-openapi.yml
  format: yaml
  label: gaipagents-com Agent Observatory API
  slug: gaipagents-com-agent-observatory-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gaipagents-com/openapi/gaipagents-com-agent-observatory-api-openapi.yml
- filename: gaipagents-com-delivery-assurance-api-openapi.yml
  format: yaml
  label: gaipagents-com Delivery Assurance API
  slug: gaipagents-com-delivery-assurance-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gaipagents-com/openapi/gaipagents-com-delivery-assurance-api-openapi.yml
- filename: gaipagents-com-discovery-api-openapi.yml
  format: yaml
  label: gaipagents-com Discovery API
  slug: gaipagents-com-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gaipagents-com/openapi/gaipagents-com-discovery-api-openapi.yml
- filename: gaipagents-com-evidence-ledger-api-openapi.yml
  format: yaml
  label: gaipagents-com Evidence Ledger API
  slug: gaipagents-com-evidence-ledger-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gaipagents-com/openapi/gaipagents-com-evidence-ledger-api-openapi.yml
- filename: gaipagents-com-platform-api-openapi.yml
  format: yaml
  label: gaipagents-com Platform API
  slug: gaipagents-com-platform-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gaipagents-com/openapi/gaipagents-com-platform-api-openapi.yml
- filename: gaipagents-com-supplier-reliability-api-openapi.yml
  format: yaml
  label: gaipagents-com Supplier Reliability API
  slug: gaipagents-com-supplier-reliability-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gaipagents-com/openapi/gaipagents-com-supplier-reliability-api-openapi.yml
- filename: gaipagents-com-the-record-api-openapi.yml
  format: yaml
  label: gaipagents-com The record API
  slug: gaipagents-com-the-record-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gaipagents-com/openapi/gaipagents-com-the-record-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: is for businesses only.
    type: business
  - text: you buy it as a consumer and the Consumer Rights Act 2015 applies
    type: individual
  minimum_age:
    text: Second Look is not aimed at children under 13.
    value: null
  restricted_uses:
  - summary: No use in breach of UK sanctions
    text: use the service in breach of UK sanctions, including for or on behalf of a person designated under them
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Both parties must confirm business purpose before GAIP gives any finding
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: gaipagents-com
provenance_date: '2026-11-09'
provider_name: gaipagents-com
provider_slug: gaipagents-com
slug: gaipagents-com-eligibility
source_date: '2026-11-09'
source_filename: gaipagents-com-eligibility.yml
source_heading: Eligibility
source_page: https://gaipagents.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: gaipagents-com\naid: gaipagents-com\nurl: https://gaipagents.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: is for businesses only.\n- type: individual\n  text: you buy it as a consumer and the Consumer Rights Act 2015 applies\nrestricted_uses:\n- summary: No use in breach of UK sanctions\n  text: use the service in breach of UK sanctions, including for or on behalf of a person designated under them\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Both parties must confirm business purpose before\
  \ GAIP gives any finding\nminimum_age:\n  value: null\n  text: Second Look is not aimed at children under 13.\n"
source_yaml_url: https://artifacts.apis.io/gaipagents-com/eligibility/gaipagents-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from gaipagents-com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- AI Agents
- MCP
- A2A
- OpenAPI
---
