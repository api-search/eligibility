---
api_specs:
- filename: anteproof-com-account-api-openapi.yml
  format: yaml
  label: Anteproof Account API
  slug: anteproof-com-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anteproof-com/openapi/anteproof-com-account-api-openapi.yml
- filename: anteproof-com-anchor-api-openapi.yml
  format: yaml
  label: Anteproof Anchor API
  slug: anteproof-com-anchor-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anteproof-com/openapi/anteproof-com-anchor-api-openapi.yml
- filename: anteproof-com-billing-api-openapi.yml
  format: yaml
  label: Anteproof Billing API
  slug: anteproof-com-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anteproof-com/openapi/anteproof-com-billing-api-openapi.yml
- filename: anteproof-com-calibration-api-openapi.yml
  format: yaml
  label: Anteproof Calibration API
  slug: anteproof-com-calibration-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anteproof-com/openapi/anteproof-com-calibration-api-openapi.yml
- filename: anteproof-com-chain-api-openapi.yml
  format: yaml
  label: Anteproof Chain API
  slug: anteproof-com-chain-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anteproof-com/openapi/anteproof-com-chain-api-openapi.yml
- filename: anteproof-com-coverage-preview-api-openapi.yml
  format: yaml
  label: Anteproof Coverage Preview API
  slug: anteproof-com-coverage-preview-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anteproof-com/openapi/anteproof-com-coverage-preview-api-openapi.yml
- filename: anteproof-com-digest-api-openapi.yml
  format: yaml
  label: Anteproof Digest API
  slug: anteproof-com-digest-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anteproof-com/openapi/anteproof-com-digest-api-openapi.yml
- filename: anteproof-com-entities-api-openapi.yml
  format: yaml
  label: Anteproof Entities API
  slug: anteproof-com-entities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anteproof-com/openapi/anteproof-com-entities-api-openapi.yml
- filename: anteproof-com-forecasts-api-openapi.yml
  format: yaml
  label: Anteproof Forecasts API
  slug: anteproof-com-forecasts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anteproof-com/openapi/anteproof-com-forecasts-api-openapi.yml
- filename: anteproof-com-freshness-api-openapi.yml
  format: yaml
  label: Anteproof Freshness API
  slug: anteproof-com-freshness-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anteproof-com/openapi/anteproof-com-freshness-api-openapi.yml
- filename: anteproof-com-me-api-openapi.yml
  format: yaml
  label: Anteproof Me API
  slug: anteproof-com-me-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anteproof-com/openapi/anteproof-com-me-api-openapi.yml
- filename: anteproof-com-proof-api-openapi.yml
  format: yaml
  label: Anteproof Proof API
  slug: anteproof-com-proof-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anteproof-com/openapi/anteproof-com-proof-api-openapi.yml
- filename: anteproof-com-questions-api-openapi.yml
  format: yaml
  label: Anteproof Questions API
  slug: anteproof-com-questions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anteproof-com/openapi/anteproof-com-questions-api-openapi.yml
- filename: anteproof-com-risk-api-openapi.yml
  format: yaml
  label: Anteproof Risk API
  slug: anteproof-com-risk-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anteproof-com/openapi/anteproof-com-risk-api-openapi.yml
- filename: anteproof-com-stats-api-openapi.yml
  format: yaml
  label: Anteproof Stats API
  slug: anteproof-com-stats-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anteproof-com/openapi/anteproof-com-stats-api-openapi.yml
- filename: anteproof-com-support-api-openapi.yml
  format: yaml
  label: Anteproof Support API
  slug: anteproof-com-support-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anteproof-com/openapi/anteproof-com-support-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you use the Service for an organisation, you confirm you may bind it.
    type: business
  minimum_age:
    text: You must be at least 16, give accurate information, and keep your sign-in method and API keys confidential.
    value: '16'
  restricted_uses:
  - summary: High-risk settings
    text: in any high-risk setting where an error could cause injury or serious loss
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
name: Anteproof
provenance_date: '2026-11-09'
provider_name: Anteproof
provider_slug: anteproof-com
slug: anteproof-com-eligibility
source_date: '2026-11-09'
source_filename: anteproof-com-eligibility.yml
source_heading: Eligibility
source_page: https://anteproof.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Anteproof\naid: anteproof-com\nurl: https://anteproof.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you use the Service for an organisation, you confirm you may bind it.\nrestricted_uses:\n- summary: High-risk settings\n  text: in any high-risk setting where an error could cause injury or serious loss\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: You must be at least 16, give accurate information, and keep your sign-in method and API keys confidential.\n"
source_yaml_url: https://artifacts.apis.io/anteproof-com/eligibility/anteproof-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Anteproof's own page on 2026-11-09.
synthetic: false
tags:
- Dependency
- Risk Management
- Analytics
- Open Source
- Software
---
