---
api_specs:
- filename: apitube-news-api-openapi.yml
  format: yaml
  label: APITube News API
  slug: apitube-news-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apitube/openapi/apitube-news-api-openapi.yml
- filename: apitube-account-api-openapi.yml
  format: yaml
  label: APITube Account API
  slug: apitube-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apitube/openapi/apitube-account-api-openapi.yml
- filename: apitube-fact-check-api-openapi.yml
  format: yaml
  label: APITube Fact Check API
  slug: apitube-fact-check-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apitube/openapi/apitube-fact-check-api-openapi.yml
- filename: apitube-reference-api-openapi.yml
  format: yaml
  label: APITube Reference API
  slug: apitube-reference-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apitube/openapi/apitube-reference-api-openapi.yml
- filename: apitube-suggest-api-openapi.yml
  format: yaml
  label: APITube Suggest API
  slug: apitube-suggest-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apitube/openapi/apitube-suggest-api-openapi.yml
- filename: apitube-system-api-openapi.yml
  format: yaml
  label: APITube System API
  slug: apitube-system-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apitube/openapi/apitube-system-api-openapi.yml
- filename: apitube-utilities-api-openapi.yml
  format: yaml
  label: APITube Utilities API
  slug: apitube-utilities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apitube/openapi/apitube-utilities-api-openapi.yml
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
  - summary: Unlawful use
    text: use the service in any manner that violates any laws directly or indirectly
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
name: APITube
provenance_date: '2026-11-09'
provider_name: APITube
provider_slug: apitube
slug: apitube-eligibility
source_date: '2026-11-09'
source_filename: apitube-eligibility.yml
source_heading: Eligibility
source_page: https://apitube.io/terms/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: APITube\naid: apitube\nurl: https://apitube.io/terms/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful use\n  text: use the service in any manner that violates any laws directly or indirectly\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/apitube/eligibility/apitube-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from APITube's own page on 2026-11-09.
synthetic: false
tags:
- News
- Media Monitoring
- News API
- Fact Check
- Journalists
---
