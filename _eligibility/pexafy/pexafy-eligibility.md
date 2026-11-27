---
api_specs:
- filename: pexafy-collections-api-openapi.yml
  format: yaml
  label: Pexafy Collections API
  slug: pexafy-collections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pexafy/openapi/pexafy-collections-api-openapi.yml
- filename: pexafy-facets-api-openapi.yml
  format: yaml
  label: Pexafy Facets API
  slug: pexafy-facets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pexafy/openapi/pexafy-facets-api-openapi.yml
- filename: pexafy-photos-api-openapi.yml
  format: yaml
  label: Pexafy Photos API
  slug: pexafy-photos-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pexafy/openapi/pexafy-photos-api-openapi.yml
- filename: pexafy-search-api-openapi.yml
  format: yaml
  label: Pexafy Search API
  slug: pexafy-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pexafy/openapi/pexafy-search-api-openapi.yml
- filename: pexafy-usage-api-openapi.yml
  format: yaml
  label: Pexafy Usage API
  slug: pexafy-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pexafy/openapi/pexafy-usage-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You must be at least 16 years old to use the Service.
    value: '16'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: To access the API, you must register and provide accurate information.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Pexafy
provenance_date: '2026-11-10'
provider_name: Pexafy
provider_slug: pexafy
slug: pexafy-eligibility
source_date: '2026-11-10'
source_filename: pexafy-eligibility.yml
source_heading: Eligibility
source_page: https://pexafy.com/legal/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Pexafy\naid: pexafy\nurl: https://pexafy.com/legal/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: To access the API, you must register and provide accurate information.\nminimum_age:\n  value: '16'\n  text: You must be at least 16 years old to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/pexafy/eligibility/pexafy-eligibility.yml
stated_fields:
- verification
- minimum_age
summary_line: 2 quoted statements, read from Pexafy's own page on 2026-11-10.
synthetic: false
tags:
- Image
- Photos
- Stock Photos
- Image Search
- Semantic Search
- Computer Vision
- Embeddings
- MCP
- Agent-Native
- Content Licensing
---
