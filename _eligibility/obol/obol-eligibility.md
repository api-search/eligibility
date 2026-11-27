---
api_specs:
- filename: obol-address-api-openapi.yml
  format: yaml
  label: Obol Address API
  slug: obol-address-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/obol/openapi/obol-address-api-openapi.yml
- filename: obol-cluster-definition-api-openapi.yml
  format: yaml
  label: Obol Cluster Definition API
  slug: obol-cluster-definition-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/obol/openapi/obol-cluster-definition-api-openapi.yml
- filename: obol-cluster-effectiveness-api-openapi.yml
  format: yaml
  label: Obol Cluster Effectiveness API
  slug: obol-cluster-effectiveness-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/obol/openapi/obol-cluster-effectiveness-api-openapi.yml
- filename: obol-cluster-lock-api-openapi.yml
  format: yaml
  label: Obol Cluster Lock API
  slug: obol-cluster-lock-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/obol/openapi/obol-cluster-lock-api-openapi.yml
- filename: obol-deposit-data-api-openapi.yml
  format: yaml
  label: Obol Deposit Data API
  slug: obol-deposit-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/obol/openapi/obol-deposit-data-api-openapi.yml
- filename: obol-dv-exit-api-openapi.yml
  format: yaml
  label: Obol DV Exit API
  slug: obol-dv-exit-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/obol/openapi/obol-dv-exit-api-openapi.yml
- filename: obol-dv-migrate-api-openapi.yml
  format: yaml
  label: Obol DV Migrate API
  slug: obol-dv-migrate-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/obol/openapi/obol-dv-migrate-api-openapi.yml
- filename: obol-fee-recipient-api-openapi.yml
  format: yaml
  label: Obol Fee Recipient API
  slug: obol-fee-recipient-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/obol/openapi/obol-fee-recipient-api-openapi.yml
- filename: obol-metrics-api-openapi.yml
  format: yaml
  label: Obol Metrics API
  slug: obol-metrics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/obol/openapi/obol-metrics-api-openapi.yml
- filename: obol-owr-information-api-openapi.yml
  format: yaml
  label: Obol OWR Information API
  slug: obol-owr-information-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/obol/openapi/obol-owr-information-api-openapi.yml
- filename: obol-positions-api-openapi.yml
  format: yaml
  label: Obol Positions API
  slug: obol-positions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/obol/openapi/obol-positions-api-openapi.yml
- filename: obol-state-api-openapi.yml
  format: yaml
  label: Obol State API
  slug: obol-state-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/obol/openapi/obol-state-api-openapi.yml
- filename: obol-system-api-openapi.yml
  format: yaml
  label: Obol System API
  slug: obol-system-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/obol/openapi/obol-system-api-openapi.yml
- filename: obol-techne-credentials-api-openapi.yml
  format: yaml
  label: Obol Techne Credentials API
  slug: obol-techne-credentials-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/obol/openapi/obol-techne-credentials-api-openapi.yml
- filename: obol-terms-and-conditions-api-openapi.yml
  format: yaml
  label: Obol Terms And Conditions API
  slug: obol-terms-and-conditions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/obol/openapi/obol-terms-and-conditions-api-openapi.yml
- filename: obol-test-api-openapi.yml
  format: yaml
  label: Obol Test API
  slug: obol-test-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/obol/openapi/obol-test-api-openapi.yml
- filename: obol-tvs-api-openapi.yml
  format: yaml
  label: Obol Tvs API
  slug: obol-tvs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/obol/openapi/obol-tvs-api-openapi.yml
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
  - summary: No illegal activity or unlicensed financial activity
    text: Use the Service or the Obol Protocol for any illegal or unauthorized purpose
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
name: Obol
provenance_date: '2026-11-10'
provider_name: Obol
provider_slug: obol
slug: obol-eligibility
source_date: '2026-11-10'
source_filename: obol-eligibility.yml
source_heading: Eligibility
source_page: https://obol.org/terms.pdf
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Obol\naid: obol\nurl: https://obol.org/terms.pdf\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: No illegal activity or unlicensed financial activity\n  text: Use the Service or the Obol Protocol for any illegal or unauthorized purpose\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/obol/eligibility/obol-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Obol's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Cryptocurrency
- Ethereum
- Staking
- Distributed Validators
- Blockchain Infrastructure
- Web3
---
