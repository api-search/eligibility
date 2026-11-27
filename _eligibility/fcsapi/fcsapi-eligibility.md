---
api_specs:
- filename: fcsapi-forex-api-openapi.yml
  format: yaml
  label: FCS API Forex API
  slug: fcsapi-forex-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fcsapi/openapi/fcsapi-forex-api-openapi.yml
- filename: fcsapi-raw-api-openapi.yml
  format: yaml
  label: FCS API Raw API
  slug: fcsapi-raw-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fcsapi/openapi/fcsapi-raw-api-openapi.yml
- filename: fcsapi-stock-api-openapi.yml
  format: yaml
  label: FCS API Stock API
  slug: fcsapi-stock-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fcsapi/openapi/fcsapi-stock-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: API data not for redistribution, or entity in any country or use by someone or where use would be contrary to local law or regulation.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful or rights-violating use
    text: you agree that you simply won't use tools for any purpose that's againts the law or prohibited by these Terms of Use.
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
name: FCS API
provenance_date: '2026-11-09'
provider_name: FCS API
provider_slug: fcsapi
slug: fcsapi-eligibility
source_date: '2026-11-09'
source_filename: fcsapi-eligibility.yml
source_heading: Eligibility
source_page: https://fcsapi.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: FCS API\naid: fcsapi\nurl: https://fcsapi.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: API data not for redistribution, or entity in any country or use by someone or where use would be contrary\n    to local law or regulation.\nentity_types: []\nrestricted_uses:\n- summary: Unlawful or rights-violating use\n  text: you agree that you simply won't use tools for any purpose that's againts the law or prohibited by these\n    Terms of Use.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/fcsapi/eligibility/fcsapi-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from FCS API's own page on 2026-11-09.
synthetic: false
tags:
- Finance
- Foreign Exchange
- Cryptocurrency
- Stocks
- Data API
---
