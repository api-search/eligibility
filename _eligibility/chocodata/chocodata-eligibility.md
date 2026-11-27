---
api_specs:
- filename: chocodata-amazon-api-openapi.yml
  format: yaml
  label: Chocodata Amazon API
  slug: chocodata-amazon-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chocodata/openapi/chocodata-amazon-api-openapi.yml
- filename: chocodata-chocodata-api-openapi.yml
  format: yaml
  label: Chocodata Chocodata API
  slug: chocodata-chocodata-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chocodata/openapi/chocodata-chocodata-api-openapi.yml
- filename: chocodata-reddit-api-openapi.yml
  format: yaml
  label: Chocodata Reddit API
  slug: chocodata-reddit-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chocodata/openapi/chocodata-reddit-api-openapi.yml
- filename: chocodata-universal-api-openapi.yml
  format: yaml
  label: Chocodata Universal API
  slug: chocodata-universal-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chocodata/openapi/chocodata-universal-api-openapi.yml
- filename: chocodata-youtube-api-openapi.yml
  format: yaml
  label: Chocodata Youtube API
  slug: chocodata-youtube-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chocodata/openapi/chocodata-youtube-api-openapi.yml
- filename: chocodata-app-store-api-openapi.yml
  format: yaml
  label: Chocodata App Store API
  slug: chocodata-app-store-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chocodata/openapi/chocodata-app-store-api-openapi.yml
- filename: chocodata-google-play-api-openapi.yml
  format: yaml
  label: Chocodata Google Play API
  slug: chocodata-google-play-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chocodata/openapi/chocodata-google-play-api-openapi.yml
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
  - summary: Non-public data collection
    text: Use the Service to collect data that is not publicly accessible
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
name: Chocodata
provenance_date: '2026-11-09'
provider_name: Chocodata
provider_slug: chocodata
slug: chocodata-eligibility
source_date: '2026-11-09'
source_filename: chocodata-eligibility.yml
source_heading: Eligibility
source_page: https://chocodata.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Chocodata\naid: chocodata\nurl: https://chocodata.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Non-public data collection\n  text: Use the Service to collect data that is not publicly accessible\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/chocodata/eligibility/chocodata-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Chocodata's own page on 2026-11-09.
synthetic: false
tags:
- Web Scraping
- Data Extraction
- SERP
- E-Commerce Data
- social-media-data
- Proxy
- MCP
- Agent-Native
- structured-json
---
