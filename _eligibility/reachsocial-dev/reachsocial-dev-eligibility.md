---
api_specs:
- filename: reachsocial-dev-catalog-api-openapi.yml
  format: yaml
  label: ReachSocial Catalog API
  slug: reachsocial-dev-catalog-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/reachsocial-dev/openapi/reachsocial-dev-catalog-api-openapi.yml
- filename: reachsocial-dev-jobs-api-openapi.yml
  format: yaml
  label: ReachSocial Jobs API
  slug: reachsocial-dev-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/reachsocial-dev/openapi/reachsocial-dev-jobs-api-openapi.yml
- filename: reachsocial-dev-operations-api-openapi.yml
  format: yaml
  label: ReachSocial Operations API
  slug: reachsocial-dev-operations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/reachsocial-dev/openapi/reachsocial-dev-operations-api-openapi.yml
- filename: reachsocial-dev-owner-api-openapi.yml
  format: yaml
  label: ReachSocial Owner API
  slug: reachsocial-dev-owner-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/reachsocial-dev/openapi/reachsocial-dev-owner-api-openapi.yml
- filename: reachsocial-dev-payments-api-openapi.yml
  format: yaml
  label: ReachSocial Payments API
  slug: reachsocial-dev-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/reachsocial-dev/openapi/reachsocial-dev-payments-api-openapi.yml
- filename: reachsocial-dev-resolve-api-openapi.yml
  format: yaml
  label: ReachSocial Resolve API
  slug: reachsocial-dev-resolve-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/reachsocial-dev/openapi/reachsocial-dev-resolve-api-openapi.yml
- filename: reachsocial-dev-services-api-openapi.yml
  format: yaml
  label: ReachSocial Services API
  slug: reachsocial-dev-services-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/reachsocial-dev/openapi/reachsocial-dev-services-api-openapi.yml
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
  - summary: Lawful use and platform terms
    text: You must use the service lawfully, comply with applicable platform terms, and protect your credentials.
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
name: ReachSocial
provenance_date: '2026-11-10'
provider_name: ReachSocial
provider_slug: reachsocial-dev
slug: reachsocial-dev-eligibility
source_date: '2026-11-10'
source_filename: reachsocial-dev-eligibility.yml
source_heading: Eligibility
source_page: https://reachsocial.dev/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ReachSocial\naid: reachsocial-dev\nurl: https://reachsocial.dev/legal/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Lawful use and platform terms\n  text: You must use the service lawfully, comply with applicable platform terms, and protect your credentials.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/reachsocial-dev/eligibility/reachsocial-dev-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from ReachSocial's own page on 2026-11-10.
synthetic: false
tags:
- Social
- Data
- Public
- Payments
---
