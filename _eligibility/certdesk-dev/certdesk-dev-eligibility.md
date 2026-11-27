---
api_specs:
- filename: certdesk-dev-certificate-api-openapi.yml
  format: yaml
  label: certdesk-dev Certificate API
  slug: certdesk-dev-certificate-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/certdesk-dev/openapi/certdesk-dev-certificate-api-openapi.yml
- filename: certdesk-dev-dns-api-openapi.yml
  format: yaml
  label: certdesk-dev Dns API
  slug: certdesk-dev-dns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/certdesk-dev/openapi/certdesk-dev-dns-api-openapi.yml
- filename: certdesk-dev-dns-info-api-openapi.yml
  format: yaml
  label: certdesk-dev Dns Info API
  slug: certdesk-dev-dns-info-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/certdesk-dev/openapi/certdesk-dev-dns-info-api-openapi.yml
- filename: certdesk-dev-expiry-api-openapi.yml
  format: yaml
  label: certdesk-dev Expiry API
  slug: certdesk-dev-expiry-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/certdesk-dev/openapi/certdesk-dev-expiry-api-openapi.yml
- filename: certdesk-dev-explain-api-openapi.yml
  format: yaml
  label: certdesk-dev Explain API
  slug: certdesk-dev-explain-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/certdesk-dev/openapi/certdesk-dev-explain-api-openapi.yml
- filename: certdesk-dev-security-api-openapi.yml
  format: yaml
  label: certdesk-dev Security API
  slug: certdesk-dev-security-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/certdesk-dev/openapi/certdesk-dev-security-api-openapi.yml
- filename: certdesk-dev-watch-api-openapi.yml
  format: yaml
  label: certdesk-dev Watch API
  slug: certdesk-dev-watch-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/certdesk-dev/openapi/certdesk-dev-watch-api-openapi.yml
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
  - summary: Unauthorized measurement targets
    text: 권한 없는 대상을 대량으로 측정하거나 측정 지점을 이용해 남의 시스템을 탐색하는 행위
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
name: certdesk-dev
provenance_date: '2026-11-09'
provider_name: certdesk-dev
provider_slug: certdesk-dev
slug: certdesk-dev-eligibility
source_date: '2026-11-09'
source_filename: certdesk-dev-eligibility.yml
source_heading: Eligibility
source_page: https://certdesk.dev/ko/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: certdesk-dev\naid: certdesk-dev\nurl: https://certdesk.dev/ko/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unauthorized measurement targets\n  text: 권한 없는 대상을 대량으로 측정하거나 측정 지점을 이용해 남의 시스템을 탐색하는 행위\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/certdesk-dev/eligibility/certdesk-dev-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from certdesk-dev's own page on 2026-11-09.
synthetic: false
tags:
- Company
---
