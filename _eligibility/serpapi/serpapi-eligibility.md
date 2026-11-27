---
api_specs:
- filename: serpapi-account-api-openapi.yml
  format: yaml
  label: SerpApi Account API
  slug: serpapi-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/serpapi/openapi/serpapi-account-api-openapi.yml
- filename: serpapi-search-api-openapi.yml
  format: yaml
  label: SerpApi Search API
  slug: serpapi-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/serpapi/openapi/serpapi-search-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: you represent that you are at least the age of majority in your state or province of residence
    type: individual
  minimum_age:
    text: you represent that you are at least the age of majority in your state or province of residence
    value: age of majority
  restricted_uses:
  - summary: Illegal use of data or service
    text: Illegal use includes, by way of example and not limitation, copyright infringement, DMCA violations, other intellectual property infringement, privacy violations, fraud, harassment, cybercrime, terrorism, child exploitation, denial-of-service attacks, or war crimes.
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
name: SerpApi
provenance_date: '2026-11-10'
provider_name: SerpApi
provider_slug: serpapi
slug: serpapi-eligibility
source_date: '2026-11-10'
source_filename: serpapi-eligibility.yml
source_heading: Eligibility
source_page: https://serpapi.com/legal
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: SerpApi\naid: serpapi\nurl: https://serpapi.com/legal\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: you represent that you are at least the age of majority in your state or province of residence\nrestricted_uses:\n- summary: Illegal use of data or service\n  text: Illegal use includes, by way of example and not limitation, copyright infringement, DMCA violations, other\n    intellectual property infringement, privacy violations, fraud, harassment, cybercrime, terrorism, child exploitation,\n    denial-of-service attacks, or war crimes.\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: age of majority\n  text: you represent that you are at least the age of majority in your state or province of residence\n"
source_yaml_url: https://artifacts.apis.io/serpapi/eligibility/serpapi-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from SerpApi's own page on 2026-11-10.
synthetic: false
tags:
- Bing
- Google
- Search
- Search Engines
- SERP
- Web Scraping
- AI Agents
- MCP
- Markdown
- Baidu
- DuckDuckGo
- YouTube
- Amazon
---
