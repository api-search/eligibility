---
api_specs:
- filename: disban-io-auth-api-openapi.yml
  format: yaml
  label: disban-io Auth API
  slug: disban-io-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/disban-io/openapi/disban-io-auth-api-openapi.yml
- filename: disban-io-batch-api-openapi.yml
  format: yaml
  label: disban-io Batch API
  slug: disban-io-batch-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/disban-io/openapi/disban-io-batch-api-openapi.yml
- filename: disban-io-check-api-openapi.yml
  format: yaml
  label: disban-io Check API
  slug: disban-io-check-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/disban-io/openapi/disban-io-check-api-openapi.yml
- filename: disban-io-features-api-openapi.yml
  format: yaml
  label: disban-io Features API
  slug: disban-io-features-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/disban-io/openapi/disban-io-features-api-openapi.yml
- filename: disban-io-keys-api-openapi.yml
  format: yaml
  label: disban-io Keys API
  slug: disban-io-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/disban-io/openapi/disban-io-keys-api-openapi.yml
- filename: disban-io-plans-api-openapi.yml
  format: yaml
  label: disban-io Plans API
  slug: disban-io-plans-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/disban-io/openapi/disban-io-plans-api-openapi.yml
- filename: disban-io-referrals-api-openapi.yml
  format: yaml
  label: disban-io Referrals API
  slug: disban-io-referrals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/disban-io/openapi/disban-io-referrals-api-openapi.yml
- filename: disban-io-subscription-api-openapi.yml
  format: yaml
  label: disban-io Subscription API
  slug: disban-io-subscription-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/disban-io/openapi/disban-io-subscription-api-openapi.yml
- filename: disban-io-webhooks-api-openapi.yml
  format: yaml
  label: disban-io Webhooks API
  slug: disban-io-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/disban-io/openapi/disban-io-webhooks-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Agent-driven activation requires the account owner’s authorization and email verification.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: disban-io
provenance_date: '2026-11-09'
provider_name: disban-io
provider_slug: disban-io
slug: disban-io-eligibility
source_date: '2026-11-09'
source_filename: disban-io-eligibility.yml
source_heading: Eligibility
source_page: https://disban.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: disban-io\naid: disban-io\nurl: https://disban.io/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Agent-driven activation requires the account owner’s authorization and email verification.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/disban-io/eligibility/disban-io-eligibility.yml
stated_fields:
- verification
summary_line: 1 quoted statement, read from disban-io's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Email
- Disposable Email
- Security
- Fraud Prevention
---
