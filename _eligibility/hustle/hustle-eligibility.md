---
api_specs:
- filename: hustle-access-token-api-openapi.yml
  format: yaml
  label: Hustle Access Token API
  slug: hustle-access-token-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hustle/openapi/hustle-access-token-api-openapi.yml
- filename: hustle-agents-api-openapi.yml
  format: yaml
  label: Hustle Agents API
  slug: hustle-agents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hustle/openapi/hustle-agents-api-openapi.yml
- filename: hustle-custom-fields-api-openapi.yml
  format: yaml
  label: Hustle Custom Fields API
  slug: hustle-custom-fields-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hustle/openapi/hustle-custom-fields-api-openapi.yml
- filename: hustle-groups-api-openapi.yml
  format: yaml
  label: Hustle Groups API
  slug: hustle-groups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hustle/openapi/hustle-groups-api-openapi.yml
- filename: hustle-integrations-api-openapi.yml
  format: yaml
  label: Hustle Integrations API
  slug: hustle-integrations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hustle/openapi/hustle-integrations-api-openapi.yml
- filename: hustle-leads-api-openapi.yml
  format: yaml
  label: Hustle Leads API
  slug: hustle-leads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hustle/openapi/hustle-leads-api-openapi.yml
- filename: hustle-messages-api-openapi.yml
  format: yaml
  label: Hustle Messages API
  slug: hustle-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hustle/openapi/hustle-messages-api-openapi.yml
- filename: hustle-organizations-api-openapi.yml
  format: yaml
  label: Hustle Organizations API
  slug: hustle-organizations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hustle/openapi/hustle-organizations-api-openapi.yml
- filename: hustle-tags-api-openapi.yml
  format: yaml
  label: Hustle Tags API
  slug: hustle-tags-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hustle/openapi/hustle-tags-api-openapi.yml
- filename: hustle-webhooks-api-openapi.yml
  format: yaml
  label: Hustle Webhooks API
  slug: hustle-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hustle/openapi/hustle-webhooks-api-openapi.yml
claim_count: 1
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
    text: Customer will not permit any user to access or use any part of the Service in a U.S.-embargoed country or region (currently Cuba, Iran, North Korea, Sudan, Syria or Crimea)
  minimum_age:
    text: null
    value: null
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
name: Hustle
provenance_date: '2026-11-09'
provider_name: Hustle
provider_slug: hustle
slug: hustle-eligibility
source_date: '2026-11-09'
source_filename: hustle-eligibility.yml
source_heading: Eligibility
source_page: https://hustle.com/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Hustle\naid: hustle\nurl: https://hustle.com/terms-and-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  - SD\n  - SY\n  text: Customer will not permit any user to access or use any part of the Service in a U.S.-embargoed country or\n    region (currently Cuba, Iran, North Korea, Sudan, Syria or Crimea)\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/hustle/eligibility/hustle-eligibility.yml
stated_fields:
- countries
summary_line: 1 quoted statement, read from Hustle's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Enterprise
- Messaging
- SMS
- Peer-to-Peer Texting
- Communications
- Marketing
- Civic Engagement
- Webhook
- OAuth
- Authentication
---
