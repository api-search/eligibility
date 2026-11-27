---
api_specs:
- filename: yepapi-email-api-openapi.yml
  format: yaml
  label: YepAPI Email API
  slug: yepapi-email-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/yepapi/openapi/yepapi-email-api-openapi.yml
- filename: yepapi-maps-api-openapi.yml
  format: yaml
  label: YepAPI Maps API
  slug: yepapi-maps-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/yepapi/openapi/yepapi-maps-api-openapi.yml
- filename: yepapi-seo-api-openapi.yml
  format: yaml
  label: YepAPI Seo API
  slug: yepapi-seo-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/yepapi/openapi/yepapi-seo-api-openapi.yml
- filename: yepapi-serp-api-openapi.yml
  format: yaml
  label: YepAPI Serp API
  slug: yepapi-serp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/yepapi/openapi/yepapi-serp-api-openapi.yml
- filename: yepapi-tiktok-api-openapi.yml
  format: yaml
  label: YepAPI Tiktok API
  slug: yepapi-tiktok-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/yepapi/openapi/yepapi-tiktok-api-openapi.yml
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
  - summary: Deepfakes and impersonation
    text: Create face swaps, deepfakes, or voice clones
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
name: YepAPI
provenance_date: '2026-11-10'
provider_name: YepAPI
provider_slug: yepapi
slug: yepapi-eligibility
source_date: '2026-11-10'
source_filename: yepapi-eligibility.yml
source_heading: Eligibility
source_page: https://www.yepapi.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: YepAPI\naid: yepapi\nurl: https://www.yepapi.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Deepfakes and impersonation\n  text: Create face swaps, deepfakes, or voice clones\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/yepapi/eligibility/yepapi-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from YepAPI's own page on 2026-11-10.
synthetic: false
tags:
- SEO
- SERP
- Web Scraping
- AI Models
- Marketing
---
