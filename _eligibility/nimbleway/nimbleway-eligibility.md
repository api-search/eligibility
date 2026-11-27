---
api_specs:
- filename: nimbleway-agents-api-openapi.yml
  format: yaml
  label: Nimbleway Agents API
  slug: nimbleway-agents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nimbleway/openapi/nimbleway-agents-api-openapi.yml
- filename: nimbleway-crawl-api-openapi.yml
  format: yaml
  label: Nimbleway Crawl API
  slug: nimbleway-crawl-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nimbleway/openapi/nimbleway-crawl-api-openapi.yml
- filename: nimbleway-domain-knowledge-api-openapi.yml
  format: yaml
  label: Nimbleway Domain Knowledge API
  slug: nimbleway-domain-knowledge-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nimbleway/openapi/nimbleway-domain-knowledge-api-openapi.yml
- filename: nimbleway-extract-api-openapi.yml
  format: yaml
  label: Nimbleway Extract API
  slug: nimbleway-extract-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nimbleway/openapi/nimbleway-extract-api-openapi.yml
- filename: nimbleway-fast-serp-api-openapi.yml
  format: yaml
  label: Nimbleway Fast SERP API
  slug: nimbleway-fast-serp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nimbleway/openapi/nimbleway-fast-serp-api-openapi.yml
- filename: nimbleway-jobs-api-openapi.yml
  format: yaml
  label: Nimbleway Jobs API
  slug: nimbleway-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nimbleway/openapi/nimbleway-jobs-api-openapi.yml
- filename: nimbleway-map-api-openapi.yml
  format: yaml
  label: Nimbleway Map API
  slug: nimbleway-map-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nimbleway/openapi/nimbleway-map-api-openapi.yml
- filename: nimbleway-media-api-openapi.yml
  format: yaml
  label: Nimbleway Media API
  slug: nimbleway-media-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nimbleway/openapi/nimbleway-media-api-openapi.yml
- filename: nimbleway-search-api-openapi.yml
  format: yaml
  label: Nimbleway Search API
  slug: nimbleway-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nimbleway/openapi/nimbleway-search-api-openapi.yml
- filename: nimbleway-serp-api-openapi.yml
  format: yaml
  label: Nimbleway SERP API
  slug: nimbleway-serp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nimbleway/openapi/nimbleway-serp-api-openapi.yml
- filename: nimbleway-tasks-api-openapi.yml
  format: yaml
  label: Nimbleway Tasks API
  slug: nimbleway-tasks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nimbleway/openapi/nimbleway-tasks-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: We provide this Site for use only by persons located in the United States.
  entity_types:
  - text: The Site is only intended for individuals aged sixteen (16) years or older.
    type: individual
  minimum_age:
    text: The Site is only intended for individuals aged sixteen (16) years or older.
    value: '16'
  restricted_uses:
  - summary: Commercial use prohibited
    text: You must not access or use for any commercial purposes any part of the Site or any services or materials available through the Site.
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
name: Nimbleway
provenance_date: '2026-11-10'
provider_name: Nimbleway
provider_slug: nimbleway
slug: nimbleway-eligibility
source_date: '2026-11-10'
source_filename: nimbleway-eligibility.yml
source_heading: Eligibility
source_page: https://www.nimbleway.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Nimbleway\naid: nimbleway\nurl: https://www.nimbleway.com/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: We provide this Site for use only by persons located in the United States.\nentity_types:\n- type: individual\n  text: The Site is only intended for individuals aged sixteen (16) years or older.\nrestricted_uses:\n- summary: Commercial use prohibited\n  text: You must not access or use for any commercial purposes any part of the Site or any services or materials\n    available through the Site.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n\
  \  text: null\nminimum_age:\n  value: '16'\n  text: The Site is only intended for individuals aged sixteen (16) years or older.\n"
source_yaml_url: https://artifacts.apis.io/nimbleway/eligibility/nimbleway-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Nimbleway's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Web Data
- Web Scraping
- Data Extraction
- Web Search
- Proxies
- AI Agents
- MCP
---
