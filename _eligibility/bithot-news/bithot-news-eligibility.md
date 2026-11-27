---
api_specs:
- filename: bithot-news-agent-api-openapi.yml
  format: yaml
  label: BITHOT Agent API
  slug: bithot-news-agent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bithot-news/openapi/bithot-news-agent-api-openapi.yml
- filename: bithot-news-dailies-api-openapi.yml
  format: yaml
  label: BITHOT Dailies API
  slug: bithot-news-dailies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bithot-news/openapi/bithot-news-dailies-api-openapi.yml
- filename: bithot-news-hot-topics-api-openapi.yml
  format: yaml
  label: BITHOT Hot Topics API
  slug: bithot-news-hot-topics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bithot-news/openapi/bithot-news-hot-topics-api-openapi.yml
- filename: bithot-news-items-api-openapi.yml
  format: yaml
  label: BITHOT Items API
  slug: bithot-news-items-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bithot-news/openapi/bithot-news-items-api-openapi.yml
- filename: bithot-news-monthlies-api-openapi.yml
  format: yaml
  label: BITHOT Monthlies API
  slug: bithot-news-monthlies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bithot-news/openapi/bithot-news-monthlies-api-openapi.yml
- filename: bithot-news-selected-api-openapi.yml
  format: yaml
  label: BITHOT Selected API
  slug: bithot-news-selected-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bithot-news/openapi/bithot-news-selected-api-openapi.yml
- filename: bithot-news-stories-api-openapi.yml
  format: yaml
  label: BITHOT Stories API
  slug: bithot-news-stories-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bithot-news/openapi/bithot-news-stories-api-openapi.yml
- filename: bithot-news-weeklies-api-openapi.yml
  format: yaml
  label: BITHOT Weeklies API
  slug: bithot-news-weeklies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bithot-news/openapi/bithot-news-weeklies-api-openapi.yml
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
  - summary: Commercial and bulk redistribution need prior consent
    text: 需要事先取得你同意的用途（例如商业产品、公开转载、批量再分发）
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
name: BITHOT
provenance_date: '2026-11-09'
provider_name: BITHOT
provider_slug: bithot-news
slug: bithot-news-eligibility
source_date: '2026-11-09'
source_filename: bithot-news-eligibility.yml
source_heading: Eligibility
source_page: https://bithot.news/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BITHOT\naid: bithot-news\nurl: https://bithot.news/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Commercial and bulk redistribution need prior consent\n  text: 需要事先取得你同意的用途（例如商业产品、公开转载、批量再分发）\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/bithot-news/eligibility/bithot-news-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from BITHOT's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Blockchain
- Cryptocurrency
- Web3
- Memecoin
- News
---
