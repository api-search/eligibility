---
api_specs:
- filename: fetchlayer-openapi-generated.yml
  format: yaml
  label: FetchLayer API
  slug: fetchlayer-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fetchlayer/openapi/_ae-authored/fetchlayer-openapi-generated.yml
- filename: fetchlayer-airbnb-api-openapi.yml
  format: yaml
  label: HootCodes Airbnb API
  slug: fetchlayer-airbnb-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fetchlayer/openapi/fetchlayer-airbnb-api-openapi.yml
- filename: fetchlayer-bing-api-openapi.yml
  format: yaml
  label: HootCodes Bing API
  slug: fetchlayer-bing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fetchlayer/openapi/fetchlayer-bing-api-openapi.yml
- filename: fetchlayer-douyin-api-openapi.yml
  format: yaml
  label: HootCodes Douyin API
  slug: fetchlayer-douyin-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fetchlayer/openapi/fetchlayer-douyin-api-openapi.yml
- filename: fetchlayer-duckduckgo-api-openapi.yml
  format: yaml
  label: HootCodes Duckduckgo API
  slug: fetchlayer-duckduckgo-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fetchlayer/openapi/fetchlayer-duckduckgo-api-openapi.yml
- filename: fetchlayer-ebay-api-openapi.yml
  format: yaml
  label: HootCodes eBay API
  slug: fetchlayer-ebay-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fetchlayer/openapi/fetchlayer-ebay-api-openapi.yml
- filename: fetchlayer-temu-api-openapi.yml
  format: yaml
  label: HootCodes Temu API
  slug: fetchlayer-temu-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fetchlayer/openapi/fetchlayer-temu-api-openapi.yml
- filename: fetchlayer-weibo-api-openapi.yml
  format: yaml
  label: HootCodes Weibo API
  slug: fetchlayer-weibo-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fetchlayer/openapi/fetchlayer-weibo-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - KP
    - SY
    served: []
    text: you are not located in, organized under, or a resident of any country or territory subject to comprehensive trade sanctions by the European Union or the U.S. Office of Foreign Assets Control (OFAC), including but not limited to Cuba, Iran, North Korea, Syria, and the Crimea, Donetsk, and Luhansk regions;
  entity_types:
  - text: FetchLayer is primarily intended for developers, businesses, and commercial use.
    type: developer
  minimum_age:
    text: You must be at least 18 years old (or the age of legal majority in your jurisdiction, if higher) to create an account or use FetchLayer.
    value: '18'
  restricted_uses:
  - summary: Unlawful surveillance or profiling
    text: build or support unlawful surveillance, unlawful profiling, or prohibited eligibility decisions;
  - summary: Sensitive personal data
    text: collect, publish, or process sensitive personal data without an appropriate legal basis;
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- CU
- IR
- KP
- SY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: HootCodes
provenance_date: '2026-11-09'
provider_name: HootCodes
provider_slug: fetchlayer
slug: fetchlayer-eligibility
source_date: '2026-11-09'
source_filename: fetchlayer-eligibility.yml
source_heading: Eligibility
source_page: https://fetchlayer.dev/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: HootCodes\naid: fetchlayer\nurl: https://fetchlayer.dev/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  - SY\n  text: you are not located in, organized under, or a resident of any country or territory subject to comprehensive\n    trade sanctions by the European Union or the U.S. Office of Foreign Assets Control (OFAC), including but not\n    limited to Cuba, Iran, North Korea, Syria, and the Crimea, Donetsk, and Luhansk regions;\nentity_types:\n- type: developer\n  text: FetchLayer is primarily intended for developers, businesses, and commercial use.\nrestricted_uses:\n\
  - summary: Unlawful surveillance or profiling\n  text: build or support unlawful surveillance, unlawful profiling, or prohibited eligibility decisions;\n- summary: Sensitive personal data\n  text: collect, publish, or process sensitive personal data without an appropriate legal basis;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old (or the age of legal majority in your jurisdiction, if higher) to create\n    an account or use FetchLayer.\n"
source_yaml_url: https://artifacts.apis.io/fetchlayer/eligibility/fetchlayer-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from HootCodes's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Social Media
- Data Extraction
- Software-as-a-Service
---
