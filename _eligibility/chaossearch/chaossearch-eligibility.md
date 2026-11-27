---
api_specs:
- filename: chaossearch-bulkexport-api-openapi.yml
  format: yaml
  label: ChaosSearch Bulkexport API
  slug: chaossearch-bulkexport-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chaossearch/openapi/chaossearch-bulkexport-api-openapi.yml
- filename: chaossearch-chaossearch-api-api-openapi.yml
  format: yaml
  label: ChaosSearch ChaosSearch API
  slug: chaossearch-chaossearch-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chaossearch/openapi/chaossearch-chaossearch-api-api-openapi.yml
- filename: chaossearch-user-api-openapi.yml
  format: yaml
  label: ChaosSearch User API
  slug: chaossearch-user-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chaossearch/openapi/chaossearch-user-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - KP
    - SD
    - SY
    served: []
    text: You are not, and are not acting on behalf of, any person who is a citizen, national, or resident of, or who is controlled by the government of Cuba, Iran, North Korea, Sudan, or Syria
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- CU
- IR
- KP
- SD
- SY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: ChaosSearch
provenance_date: '2026-11-09'
provider_name: ChaosSearch
provider_slug: chaossearch
slug: chaossearch-eligibility
source_date: '2026-11-09'
source_filename: chaossearch-eligibility.yml
source_heading: Eligibility
source_page: https://www.chaossearch.io/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ChaosSearch\naid: chaossearch\nurl: https://www.chaossearch.io/legal/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  - SD\n  - SY\n  text: You are not, and are not acting on behalf of, any person who is a citizen, national, or resident of, or\n    who is controlled by the government of Cuba, Iran, North Korea, Sudan, or Syria\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/chaossearch/eligibility/chaossearch-eligibility.yml
stated_fields:
- countries
summary_line: 1 quoted statement, read from ChaosSearch's own page on 2026-11-09.
synthetic: false
tags:
- Analytics
- Observability
- Security
- Data Lake
- Cloud Storage
- ELK
---
