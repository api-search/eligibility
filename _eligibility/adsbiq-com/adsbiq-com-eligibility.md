---
api_specs:
- filename: adsbiq-com-aircraft-api-openapi.yml
  format: yaml
  label: adsbiq-com Aircraft API
  slug: adsbiq-com-aircraft-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/adsbiq-com/openapi/adsbiq-com-aircraft-api-openapi.yml
- filename: adsbiq-com-airports-api-openapi.yml
  format: yaml
  label: adsbiq-com Airports API
  slug: adsbiq-com-airports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/adsbiq-com/openapi/adsbiq-com-airports-api-openapi.yml
- filename: adsbiq-com-flights-api-openapi.yml
  format: yaml
  label: adsbiq-com Flights API
  slug: adsbiq-com-flights-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/adsbiq-com/openapi/adsbiq-com-flights-api-openapi.yml
- filename: adsbiq-com-geographic-api-openapi.yml
  format: yaml
  label: adsbiq-com Geographic API
  slug: adsbiq-com-geographic-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/adsbiq-com/openapi/adsbiq-com-geographic-api-openapi.yml
- filename: adsbiq-com-network-api-openapi.yml
  format: yaml
  label: adsbiq-com Network API
  slug: adsbiq-com-network-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/adsbiq-com/openapi/adsbiq-com-network-api-openapi.yml
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
  - summary: Safety-critical use
    text: The Service is not intended for use in air traffic control, flight safety, navigation, or any safety-critical application.
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
name: adsbiq-com
provenance_date: '2026-11-09'
provider_name: adsbiq-com
provider_slug: adsbiq-com
slug: adsbiq-com-eligibility
source_date: '2026-11-09'
source_filename: adsbiq-com-eligibility.yml
source_heading: Eligibility
source_page: https://adsbiq.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: adsbiq-com\naid: adsbiq-com\nurl: https://adsbiq.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Safety-critical use\n  text: The Service is not intended for use in air traffic control, flight safety, navigation, or any safety-critical\n    application.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/adsbiq-com/eligibility/adsbiq-com-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from adsbiq-com's own page on 2026-11-09.
synthetic: false
tags:
- Advertising
- Data Analytics
- Marketing Technology
- Company
---
