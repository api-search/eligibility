---
api_specs:
- filename: viber-account-api-openapi.yml
  format: yaml
  label: Rakuten Viber Account API
  slug: viber-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/viber/openapi/viber-account-api-openapi.yml
- filename: viber-messages-api-openapi.yml
  format: yaml
  label: Rakuten Viber Messages API
  slug: viber-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/viber/openapi/viber-messages-api-openapi.yml
- filename: viber-users-api-openapi.yml
  format: yaml
  label: Rakuten Viber Users API
  slug: viber-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/viber/openapi/viber-users-api-openapi.yml
- filename: viber-webhooks-api-openapi.yml
  format: yaml
  label: Rakuten Viber Webhooks API
  slug: viber-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/viber/openapi/viber-webhooks-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The service might not be available in your country. Viber payment services are only available in certain countries.
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
name: Rakuten Viber
provenance_date: '2026-11-10'
provider_name: Rakuten Viber
provider_slug: viber
slug: viber-eligibility
source_date: '2026-11-10'
source_filename: viber-eligibility.yml
source_heading: Eligibility
source_page: https://www.viber.com/en/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Rakuten Viber\naid: viber\nurl: https://www.viber.com/en/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The service might not be available in your country. Viber payment services are only available in certain\n    countries.\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/viber/eligibility/viber-eligibility.yml
stated_fields:
- countries
summary_line: 1 quoted statement, read from Rakuten Viber's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Messaging
- Chatbots
- Communications
---
