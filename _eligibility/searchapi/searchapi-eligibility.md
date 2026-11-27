---
api_specs:
- filename: searchapi-search-api-openapi.yml
  format: yaml
  label: SearchApi SERP API
  slug: searchapi-serp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/searchapi/openapi/searchapi-search-api-openapi.yml
- filename: searchapi-account-api-openapi.yml
  format: yaml
  label: SearchApi Account & Analytics API
  slug: searchapi-account-analytics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/searchapi/openapi/searchapi-account-api-openapi.yml
- filename: searchapi-analytics-api-openapi.yml
  format: yaml
  label: SearchApi Analytics API
  slug: searchapi-analytics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/searchapi/openapi/searchapi-analytics-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be a human. Accounts registered by “bots” or other automated methods are not permitted.
    type: individual
  - text: Organizations may have multiple accounts for different departments or team members, but each account must represent a distinct individual.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Illegal activities
    text: You may not use the Services for any illegal activities, including but not limited to cyber criminality, terrorism, child sexual abuse material (CSAM), denial of service attacks, war crimes, unauthorized access to systems, or any other actions that violate U.S. federal laws.
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
name: SearchApi
provenance_date: '2026-11-10'
provider_name: SearchApi
provider_slug: searchapi
slug: searchapi-eligibility
source_date: '2026-11-10'
source_filename: searchapi-eligibility.yml
source_heading: Eligibility
source_page: https://www.searchapi.io/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: SearchApi\naid: searchapi\nurl: https://www.searchapi.io/legal/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be a human. Accounts registered by “bots” or other automated methods are not permitted.\n- type: business\n  text: Organizations may have multiple accounts for different departments or team members, but each account must\n    represent a distinct individual.\nrestricted_uses:\n- summary: Illegal activities\n  text: You may not use the Services for any illegal activities, including but not limited to cyber criminality,\n\
  \    terrorism, child sexual abuse material (CSAM), denial of service attacks, war crimes, unauthorized access to\n    systems, or any other actions that violate U.S. federal laws.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/searchapi/eligibility/searchapi-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from SearchApi's own page on 2026-11-10.
synthetic: false
tags:
- Search
- SERP
- Google Search
- Web Scraping
- Search data
- Market Intelligence
- SEO
- MCP
- Agent-Native
---
