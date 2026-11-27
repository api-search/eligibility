---
api_specs:
- filename: rendex-dev-account-api-openapi.yml
  format: yaml
  label: rendex-dev Account API
  slug: rendex-dev-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rendex-dev/openapi/rendex-dev-account-api-openapi.yml
- filename: rendex-dev-batch-api-openapi.yml
  format: yaml
  label: rendex-dev Batch API
  slug: rendex-dev-batch-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rendex-dev/openapi/rendex-dev-batch-api-openapi.yml
- filename: rendex-dev-health-api-openapi.yml
  format: yaml
  label: rendex-dev Health API
  slug: rendex-dev-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rendex-dev/openapi/rendex-dev-health-api-openapi.yml
- filename: rendex-dev-jobs-api-openapi.yml
  format: yaml
  label: rendex-dev Jobs API
  slug: rendex-dev-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rendex-dev/openapi/rendex-dev-jobs-api-openapi.yml
- filename: rendex-dev-screenshot-api-openapi.yml
  format: yaml
  label: rendex-dev Screenshot API
  slug: rendex-dev-screenshot-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rendex-dev/openapi/rendex-dev-screenshot-api-openapi.yml
- filename: rendex-dev-watch-api-openapi.yml
  format: yaml
  label: rendex-dev Watch API
  slug: rendex-dev-watch-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rendex-dev/openapi/rendex-dev-watch-api-openapi.yml
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
  restricted_uses:
  - summary: Phishing, fraud, deception
    text: Generate screenshots for phishing, impersonation, fraud, or any deceptive purpose.
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
name: rendex-dev
provenance_date: '2026-11-10'
provider_name: rendex-dev
provider_slug: rendex-dev
slug: rendex-dev-eligibility
source_date: '2026-11-10'
source_filename: rendex-dev-eligibility.yml
source_heading: Eligibility
source_page: https://rendex.dev/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: rendex-dev\naid: rendex-dev\nurl: https://rendex.dev/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Phishing, fraud, deception\n  text: Generate screenshots for phishing, impersonation, fraud, or any deceptive purpose.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/rendex-dev/eligibility/rendex-dev-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from rendex-dev's own page on 2026-11-10.
synthetic: false
tags:
- Rendering
- Screenshots
- PDF
- Automation
---
