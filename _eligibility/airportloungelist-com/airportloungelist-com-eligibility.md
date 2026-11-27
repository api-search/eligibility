---
api_specs:
- filename: airportloungelist-com-access-api-openapi.yml
  format: yaml
  label: Airport Lounge List Access API
  slug: airportloungelist-com-access-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/airportloungelist-com/openapi/airportloungelist-com-access-api-openapi.yml
- filename: airportloungelist-com-airports-api-openapi.yml
  format: yaml
  label: Airport Lounge List Airports API
  slug: airportloungelist-com-airports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/airportloungelist-com/openapi/airportloungelist-com-airports-api-openapi.yml
- filename: airportloungelist-com-lounges-api-openapi.yml
  format: yaml
  label: Airport Lounge List Lounges API
  slug: airportloungelist-com-lounges-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/airportloungelist-com/openapi/airportloungelist-com-lounges-api-openapi.yml
- filename: airportloungelist-com-networks-api-openapi.yml
  format: yaml
  label: Airport Lounge List Networks API
  slug: airportloungelist-com-networks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/airportloungelist-com/openapi/airportloungelist-com-networks-api-openapi.yml
claim_count: 2
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
  - summary: No bulk scraping or competing database
    text: You must not circumvent our rate limits, scrape the Service in bulk, resell the lounge data as a competing database, or use the Service to build a substantially similar directory.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: To write reviews, log visits, or keep a wishlist you must create a free account.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Airport Lounge List
provenance_date: '2026-11-09'
provider_name: Airport Lounge List
provider_slug: airportloungelist-com
slug: airportloungelist-com-eligibility
source_date: '2026-11-09'
source_filename: airportloungelist-com-eligibility.yml
source_heading: Eligibility
source_page: https://airportloungelist.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Airport Lounge List\naid: airportloungelist-com\nurl: https://airportloungelist.com/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: No bulk scraping or competing database\n  text: You must not circumvent our rate limits, scrape the Service in bulk, resell the lounge data as a competing\n    database, or use the Service to build a substantially similar directory.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: To write reviews, log visits, or keep a wishlist you must create a free account.\n\
  minimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/airportloungelist-com/eligibility/airportloungelist-com-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from Airport Lounge List's own page on 2026-11-09.
synthetic: false
tags:
- Airport
- Travel
- Lounge
- Aviation
- Comparison
- Company
---
