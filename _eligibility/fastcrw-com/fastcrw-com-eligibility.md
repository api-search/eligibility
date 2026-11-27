---
api_specs:
- filename: fastcrw-com-batch-api-openapi.yml
  format: yaml
  label: fastcrw-com Batch API
  slug: fastcrw-com-batch-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fastcrw-com/openapi/fastcrw-com-batch-api-openapi.yml
- filename: fastcrw-com-capabilities-api-openapi.yml
  format: yaml
  label: fastcrw-com Capabilities API
  slug: fastcrw-com-capabilities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fastcrw-com/openapi/fastcrw-com-capabilities-api-openapi.yml
- filename: fastcrw-com-change-tracking-api-openapi.yml
  format: yaml
  label: fastcrw-com Change Tracking API
  slug: fastcrw-com-change-tracking-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fastcrw-com/openapi/fastcrw-com-change-tracking-api-openapi.yml
- filename: fastcrw-com-crawl-api-openapi.yml
  format: yaml
  label: fastcrw-com Crawl API
  slug: fastcrw-com-crawl-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fastcrw-com/openapi/fastcrw-com-crawl-api-openapi.yml
- filename: fastcrw-com-extract-api-openapi.yml
  format: yaml
  label: fastcrw-com Extract API
  slug: fastcrw-com-extract-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fastcrw-com/openapi/fastcrw-com-extract-api-openapi.yml
- filename: fastcrw-com-map-api-openapi.yml
  format: yaml
  label: fastcrw-com Map API
  slug: fastcrw-com-map-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fastcrw-com/openapi/fastcrw-com-map-api-openapi.yml
- filename: fastcrw-com-scrape-api-openapi.yml
  format: yaml
  label: fastcrw-com Scrape API
  slug: fastcrw-com-scrape-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fastcrw-com/openapi/fastcrw-com-scrape-api-openapi.yml
- filename: fastcrw-com-search-api-openapi.yml
  format: yaml
  label: fastcrw-com Search API
  slug: fastcrw-com-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fastcrw-com/openapi/fastcrw-com-search-api-openapi.yml
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
  - summary: Unauthorized target content
    text: Target login-walled or authenticated-only content that the caller is not authorized to access
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
name: fastcrw-com
provenance_date: '2026-11-09'
provider_name: fastcrw-com
provider_slug: fastcrw-com
slug: fastcrw-com-eligibility
source_date: '2026-11-09'
source_filename: fastcrw-com-eligibility.yml
source_heading: Eligibility
source_page: https://fastcrw.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: fastcrw-com\naid: fastcrw-com\nurl: https://fastcrw.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unauthorized target content\n  text: Target login-walled or authenticated-only content that the caller is not authorized to access\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/fastcrw-com/eligibility/fastcrw-com-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from fastcrw-com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Web Scraping
- AI Agents
- Rust
- Open Source
- SERP
---
