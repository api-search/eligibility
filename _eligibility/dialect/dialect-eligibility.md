---
api_specs:
- filename: dialect-blink-api-openapi.yml
  format: yaml
  label: Dialect Blink API
  slug: dialect-blink-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dialect/openapi/dialect-blink-api-openapi.yml
- filename: dialect-blink-data-table-api-openapi.yml
  format: yaml
  label: Dialect Blink Data Table API
  slug: dialect-blink-data-table-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dialect/openapi/dialect-blink-data-table-api-openapi.yml
- filename: dialect-blink-lists-api-openapi.yml
  format: yaml
  label: Dialect Blink Lists API
  slug: dialect-blink-lists-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dialect/openapi/dialect-blink-lists-api-openapi.yml
- filename: dialect-blink-preview-api-openapi.yml
  format: yaml
  label: Dialect Blink Preview API
  slug: dialect-blink-preview-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dialect/openapi/dialect-blink-preview-api-openapi.yml
- filename: dialect-channels-api-openapi.yml
  format: yaml
  label: Dialect Channels API
  slug: dialect-channels-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dialect/openapi/dialect-channels-api-openapi.yml
- filename: dialect-inbox-api-openapi.yml
  format: yaml
  label: Dialect Inbox API
  slug: dialect-inbox-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dialect/openapi/dialect-inbox-api-openapi.yml
- filename: dialect-markets-api-openapi.yml
  format: yaml
  label: Dialect Markets API
  slug: dialect-markets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dialect/openapi/dialect-markets-api-openapi.yml
- filename: dialect-positions-api-openapi.yml
  format: yaml
  label: Dialect Positions API
  slug: dialect-positions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dialect/openapi/dialect-positions-api-openapi.yml
- filename: dialect-send-api-openapi.yml
  format: yaml
  label: Dialect Send API
  slug: dialect-send-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dialect/openapi/dialect-send-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You represent and warrant that you are not located in, ordinarily resident in, or organized under the laws of any jurisdiction that is subject to a comprehensive U.S. Government embargo
  entity_types:
  - text: if you are an individual, are not at least 18 years of age
    type: individual
  - text: If you use the Service on behalf of a co±mpany or other entity then “you” includes you and that entity, and you represent and warrant that (a) you are an authorized representative of the entity
    type: business
  minimum_age:
    text: if you are an individual, are not at least 18 years of age and, in any event, of a legal capacity to form a binding contract
    value: '18'
  restricted_uses:
  - summary: Sanctions and embargoed jurisdictions
    text: you are not subject to any sanctions administered by an agency of the U.S. Government, any other government, or the United Nations
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
name: Dialect
provenance_date: '2026-11-09'
provider_name: Dialect
provider_slug: dialect
slug: dialect-eligibility
source_date: '2026-11-09'
source_filename: dialect-eligibility.yml
source_heading: Eligibility
source_page: https://legal.dialect.to/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Dialect\naid: dialect\nurl: https://legal.dialect.to/tos\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You represent and warrant that you are not located in, ordinarily resident in, or organized under the laws\n    of any jurisdiction that is subject to a comprehensive U.S. Government embargo\nentity_types:\n- type: individual\n  text: if you are an individual, are not at least 18 years of age\n- type: business\n  text: If you use the Service on behalf of a co±mpany or other entity then “you” includes you and that entity,\n    and you represent and warrant that (a) you are an authorized\
  \ representative of the entity\nrestricted_uses:\n- summary: Sanctions and embargoed jurisdictions\n  text: you are not subject to any sanctions administered by an agency of the U.S. Government, any other government,\n    or the United Nations\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: if you are an individual, are not at least 18 years of age and, in any event, of a legal capacity to form\n    a binding contract\n"
source_yaml_url: https://artifacts.apis.io/dialect/eligibility/dialect-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Dialect's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Infrastructure
- Web3
- Blockchain
- Solana
- Notification
- Messaging
- Alerts
- DeFi
- Payments
- Agents
- MCP
---
