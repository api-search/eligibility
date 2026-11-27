---
api_specs:
- filename: concentrate-decisions-api-openapi.yml
  format: yaml
  label: Concentrate Decisions API
  slug: concentrate-decisions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/concentrate/openapi/concentrate-decisions-api-openapi.yml
- filename: concentrate-messages-api-openapi.yml
  format: yaml
  label: Concentrate Messages API
  slug: concentrate-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/concentrate/openapi/concentrate-messages-api-openapi.yml
- filename: concentrate-models-api-openapi.yml
  format: yaml
  label: Concentrate Models API
  slug: concentrate-models-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/concentrate/openapi/concentrate-models-api-openapi.yml
- filename: concentrate-responses-api-openapi.yml
  format: yaml
  label: Concentrate Responses API
  slug: concentrate-responses-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/concentrate/openapi/concentrate-responses-api-openapi.yml
- filename: concentrate-systemone-api-openapi.yml
  format: yaml
  label: Concentrate Systemone API
  slug: concentrate-systemone-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/concentrate/openapi/concentrate-systemone-api-openapi.yml
- filename: concentrate-chat-completions-api-openapi.yml
  format: yaml
  label: Concentrate Chat Completions API
  slug: concentrate-chat-completions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/concentrate/openapi/concentrate-chat-completions-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are entering into this Agreement on behalf of an organization, you represent that you have authority to bind that entity to these terms.
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
name: Concentrate
provenance_date: '2026-11-09'
provider_name: Concentrate
provider_slug: concentrate
slug: concentrate-eligibility
source_date: '2026-11-09'
source_filename: concentrate-eligibility.yml
source_heading: Eligibility
source_page: https://concentrate.ai/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Concentrate\naid: concentrate\nurl: https://concentrate.ai/legal/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are entering into this Agreement on behalf of an organization, you represent that you have authority\n    to bind that entity to these terms.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/concentrate/eligibility/concentrate-eligibility.yml
stated_fields:
- entity_types
summary_line: 1 quoted statement, read from Concentrate's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- LLM
- Gateways
- Platform
---
