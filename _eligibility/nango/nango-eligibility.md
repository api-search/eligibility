---
api_specs:
- filename: nango-actions-api-openapi.yml
  format: yaml
  label: Nango Actions API
  slug: nango-actions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nango/openapi/nango-actions-api-openapi.yml
- filename: nango-connections-api-openapi.yml
  format: yaml
  label: Nango Connections API
  slug: nango-connections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nango/openapi/nango-connections-api-openapi.yml
- filename: nango-integrations-api-openapi.yml
  format: yaml
  label: Nango Integrations API
  slug: nango-integrations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nango/openapi/nango-integrations-api-openapi.yml
- filename: nango-proxy-api-openapi.yml
  format: yaml
  label: Nango Proxy API
  slug: nango-proxy-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nango/openapi/nango-proxy-api-openapi.yml
- filename: nango-syncs-api-openapi.yml
  format: yaml
  label: Nango Syncs API
  slug: nango-syncs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nango/openapi/nango-syncs-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - KP
    - SD
    - SY
    served: []
    text: Customer may not access the Nango Services if Customer is located in a territory where U.S. businesses are prohibited from engaging in business (such as Cuba, Iran, North Korea, Sudan, or Syria)
  entity_types:
  - text: Customer, if an individual, is at least 18 years of age
    type: individual
  - text: If you are accessing, purchasing or using the Nango Services on behalf of your company, you represent that you are authorized to accept this Agreement on behalf of your company
    type: business
  minimum_age:
    text: Customer, if an individual, is at least 18 years of age
    value: '18'
  restricted_uses:
  - summary: Illegal or infringing use
    text: use the Nango Services for any illegal purpose, or in violation of any local, state, national, or international law;
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- CU
- IR
- KP
- SD
- SY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Nango
provenance_date: '2026-11-10'
provider_name: Nango
provider_slug: nango
slug: nango-eligibility
source_date: '2026-11-10'
source_filename: nango-eligibility.yml
source_heading: Eligibility
source_page: https://nango.dev/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Nango\naid: nango\nurl: https://nango.dev/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  - SD\n  - SY\n  text: Customer may not access the Nango Services if Customer is located in a territory where U.S. businesses are\n    prohibited from engaging in business (such as Cuba, Iran, North Korea, Sudan, or Syria)\nentity_types:\n- type: individual\n  text: Customer, if an individual, is at least 18 years of age\n- type: business\n  text: If you are accessing, purchasing or using the Nango Services on behalf of your company, you represent that\n    you are authorized\
  \ to accept this Agreement on behalf of your company\nrestricted_uses:\n- summary: Illegal or infringing use\n  text: use the Nango Services for any illegal purpose, or in violation of any local, state, national, or international\n    law;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Customer, if an individual, is at least 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/nango/eligibility/nango-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Nango's own page on 2026-11-10.
synthetic: false
tags:
- AI Agents
- Integration
- OAuth
- Syncing
- Unified API
- Webhook
- Authentication
---
