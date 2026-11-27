---
api_specs:
- filename: clawvisor-auth-api-openapi.yml
  format: yaml
  label: Clawvisor Auth API
  slug: clawvisor-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clawvisor/openapi/clawvisor-auth-api-openapi.yml
- filename: clawvisor-catalog-api-openapi.yml
  format: yaml
  label: Clawvisor Catalog API
  slug: clawvisor-catalog-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clawvisor/openapi/clawvisor-catalog-api-openapi.yml
- filename: clawvisor-gateway-api-openapi.yml
  format: yaml
  label: Clawvisor Gateway API
  slug: clawvisor-gateway-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clawvisor/openapi/clawvisor-gateway-api-openapi.yml
- filename: clawvisor-tasks-api-openapi.yml
  format: yaml
  label: Clawvisor Tasks API
  slug: clawvisor-tasks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clawvisor/openapi/clawvisor-tasks-api-openapi.yml
- filename: clawvisor-tokens-api-openapi.yml
  format: yaml
  label: Clawvisor Tokens API
  slug: clawvisor-tokens-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clawvisor/openapi/clawvisor-tokens-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful use
    text: You must not use the Service or the Software for any unlawful purpose or in violation of any applicable laws.
  - summary: Bypassing third-party provider controls
    text: You must not use the Service or the Software to bypass or evade any third-party provider's usage limits, safety systems, authorization model, account restrictions, credential requirements, or access controls.
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
name: Clawvisor
provenance_date: '2026-11-09'
provider_name: Clawvisor
provider_slug: clawvisor
slug: clawvisor-eligibility
source_date: '2026-11-09'
source_filename: clawvisor-eligibility.yml
source_heading: Eligibility
source_page: https://clawvisor.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Clawvisor\naid: clawvisor\nurl: https://clawvisor.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful use\n  text: You must not use the Service or the Software for any unlawful purpose or in violation of any applicable\n    laws.\n- summary: Bypassing third-party provider controls\n  text: You must not use the Service or the Software to bypass or evade any third-party provider's usage limits,\n    safety systems, authorization model, account restrictions, credential requirements, or access controls.\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/clawvisor/eligibility/clawvisor-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 2 quoted statements, read from Clawvisor's own page on 2026-11-09.
synthetic: false
tags:
- AI Agents
- Authorization
- Security
- Identity
- Access Control
- MCP
- Credential Management
- Governance
- Developer Tools
---
