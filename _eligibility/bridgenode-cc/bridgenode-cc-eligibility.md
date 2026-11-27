---
api_specs:
- filename: bridgenode-cc-models-api-openapi.yml
  format: yaml
  label: BridgeNode Models API
  slug: bridgenode-cc-models-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bridgenode-cc/openapi/bridgenode-cc-models-api-openapi.yml
- filename: bridgenode-cc-chat-completions-api-openapi.yml
  format: yaml
  label: BridgeNode Chat Completions API
  slug: bridgenode-cc-chat-completions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bridgenode-cc/openapi/bridgenode-cc-chat-completions-api-openapi.yml
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
  - summary: Unlawful purposes
    text: You agree not to use the service for unlawful purposes
  verification:
    approval_required: false
    kyb: null
    kyc: false
    text: No API keys or accounts are required.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: BridgeNode
provenance_date: '2026-11-09'
provider_name: BridgeNode
provider_slug: bridgenode-cc
slug: bridgenode-cc-eligibility
source_date: '2026-11-09'
source_filename: bridgenode-cc-eligibility.yml
source_heading: Eligibility
source_page: https://bridgenode.cc/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BridgeNode\naid: bridgenode-cc\nurl: https://bridgenode.cc/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful purposes\n  text: You agree not to use the service for unlawful purposes\nverification:\n  kyc: false\n  kyb: null\n  approval_required: false\n  text: No API keys or accounts are required.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/bridgenode-cc/eligibility/bridgenode-cc-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from BridgeNode's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Inference
- Payments
- Solana
- OpenAI-Compatible
---
