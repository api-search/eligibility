---
api_specs:
- filename: refinitiv-eikon-asyncapi.yml
  format: yaml
  label: LSEG WebSocket API
  slug: lseg-websocket-api
  spec_type: AsyncAPI
  url: https://artifacts.apis.io/refinitiv-eikon/asyncapi/refinitiv-eikon-asyncapi.yml
- filename: refinitiv-eikon-authentication-api-openapi.yml
  format: yaml
  label: Refinitiv Eikon Authentication API
  slug: refinitiv-eikon-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/refinitiv-eikon/openapi/refinitiv-eikon-authentication-api-openapi.yml
- filename: refinitiv-eikon-esg-api-openapi.yml
  format: yaml
  label: Refinitiv Eikon ESG API
  slug: refinitiv-eikon-esg-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/refinitiv-eikon/openapi/refinitiv-eikon-esg-api-openapi.yml
- filename: refinitiv-eikon-extractions-api-openapi.yml
  format: yaml
  label: Refinitiv Eikon Extractions API
  slug: refinitiv-eikon-extractions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/refinitiv-eikon/openapi/refinitiv-eikon-extractions-api-openapi.yml
- filename: refinitiv-eikon-files-api-openapi.yml
  format: yaml
  label: Refinitiv Eikon Files API
  slug: refinitiv-eikon-files-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/refinitiv-eikon/openapi/refinitiv-eikon-files-api-openapi.yml
- filename: refinitiv-eikon-historical-pricing-api-openapi.yml
  format: yaml
  label: Refinitiv Eikon Historical Pricing API
  slug: refinitiv-eikon-historical-pricing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/refinitiv-eikon/openapi/refinitiv-eikon-historical-pricing-api-openapi.yml
- filename: refinitiv-eikon-instrument-lists-api-openapi.yml
  format: yaml
  label: Refinitiv Eikon Instrument Lists API
  slug: refinitiv-eikon-instrument-lists-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/refinitiv-eikon/openapi/refinitiv-eikon-instrument-lists-api-openapi.yml
- filename: refinitiv-eikon-jobs-api-openapi.yml
  format: yaml
  label: Refinitiv Eikon Jobs API
  slug: refinitiv-eikon-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/refinitiv-eikon/openapi/refinitiv-eikon-jobs-api-openapi.yml
- filename: refinitiv-eikon-news-api-openapi.yml
  format: yaml
  label: Refinitiv Eikon News API
  slug: refinitiv-eikon-news-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/refinitiv-eikon/openapi/refinitiv-eikon-news-api-openapi.yml
- filename: refinitiv-eikon-on-demand-extractions-api-openapi.yml
  format: yaml
  label: Refinitiv Eikon On-Demand Extractions API
  slug: refinitiv-eikon-on-demand-extractions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/refinitiv-eikon/openapi/refinitiv-eikon-on-demand-extractions-api-openapi.yml
- filename: refinitiv-eikon-report-templates-api-openapi.yml
  format: yaml
  label: Refinitiv Eikon Report Templates API
  slug: refinitiv-eikon-report-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/refinitiv-eikon/openapi/refinitiv-eikon-report-templates-api-openapi.yml
- filename: refinitiv-eikon-schedules-api-openapi.yml
  format: yaml
  label: Refinitiv Eikon Schedules API
  slug: refinitiv-eikon-schedules-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/refinitiv-eikon/openapi/refinitiv-eikon-schedules-api-openapi.yml
- filename: refinitiv-eikon-search-api-openapi.yml
  format: yaml
  label: Refinitiv Eikon Search API
  slug: refinitiv-eikon-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/refinitiv-eikon/openapi/refinitiv-eikon-search-api-openapi.yml
- filename: refinitiv-eikon-streaming-pricing-api-openapi.yml
  format: yaml
  label: Refinitiv Eikon Streaming Pricing API
  slug: refinitiv-eikon-streaming-pricing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/refinitiv-eikon/openapi/refinitiv-eikon-streaming-pricing-api-openapi.yml
- filename: refinitiv-eikon-symbology-api-openapi.yml
  format: yaml
  label: Refinitiv Eikon Symbology API
  slug: refinitiv-eikon-symbology-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/refinitiv-eikon/openapi/refinitiv-eikon-symbology-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Please note that the provision of investment services may be restricted in certain jurisdictions. The information on this Website is not intended for distribution to or use by any person or entity in any jurisdiction or country where such distribution would be contrary to local law or regulation.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: investment reliance
    text: Information on the Website does not constitute professional, legal, regulatory, financial or investment advice and must not be used as a basis for making investment decisions
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
name: Refinitiv Eikon
provenance_date: '2026-11-10'
provider_name: Refinitiv Eikon
provider_slug: refinitiv-eikon
slug: refinitiv-eikon-eligibility
source_date: '2026-11-10'
source_filename: refinitiv-eikon-eligibility.yml
source_heading: Eligibility
source_page: https://www.lseg.com/en/policies/website-terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Refinitiv Eikon\naid: refinitiv-eikon\nurl: https://www.lseg.com/en/policies/website-terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Please note that the provision of investment services may be restricted in certain jurisdictions. The information\n    on this Website is not intended for distribution to or use by any person or entity in any jurisdiction or country\n    where such distribution would be contrary to local law or regulation.\nentity_types: []\nrestricted_uses:\n- summary: investment reliance\n  text: Information on the Website does not constitute professional,\
  \ legal, regulatory, financial or investment\n    advice and must not be used as a basis for making investment decisions\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/refinitiv-eikon/eligibility/refinitiv-eikon-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from Refinitiv Eikon's own page on 2026-11-10.
synthetic: false
tags:
- Analytics
- Financial Data
- Financial News
- Market Data
- Real-Time Data
- Trading
- Real-Time
---
