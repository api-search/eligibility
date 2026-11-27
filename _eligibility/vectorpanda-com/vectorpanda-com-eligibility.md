---
api_specs:
- filename: vectorpanda-com-collections-api-openapi.yml
  format: yaml
  label: vectorpanda-com Collections API
  slug: vectorpanda-com-collections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vectorpanda-com/openapi/vectorpanda-com-collections-api-openapi.yml
- filename: vectorpanda-com-health-api-openapi.yml
  format: yaml
  label: vectorpanda-com Health API
  slug: vectorpanda-com-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vectorpanda-com/openapi/vectorpanda-com-health-api-openapi.yml
- filename: vectorpanda-com-query-api-openapi.yml
  format: yaml
  label: vectorpanda-com Query API
  slug: vectorpanda-com-query-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vectorpanda-com/openapi/vectorpanda-com-query-api-openapi.yml
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
  - summary: Illegal content or activity
    text: Store illegal content or facilitate illegal activity
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
name: vectorpanda-com
provenance_date: '2026-11-10'
provider_name: vectorpanda-com
provider_slug: vectorpanda-com
slug: vectorpanda-com-eligibility
source_date: '2026-11-10'
source_filename: vectorpanda-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.vectorpanda.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: vectorpanda-com\naid: vectorpanda-com\nurl: https://www.vectorpanda.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Illegal content or activity\n  text: Store illegal content or facilitate illegal activity\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/vectorpanda-com/eligibility/vectorpanda-com-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from vectorpanda-com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Vector Search
- Semantic Search
- Embeddings
---
