---
api_specs:
- filename: ssen-catalog-api-openapi.yml
  format: yaml
  label: Scottish and Southern Electricity Networks Catalog API
  slug: ssen-catalog-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ssen/openapi/ssen-catalog-api-openapi.yml
- filename: ssen-dataset-api-openapi.yml
  format: yaml
  label: Scottish and Southern Electricity Networks Dataset API
  slug: ssen-dataset-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ssen/openapi/ssen-dataset-api-openapi.yml
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
  - summary: Logo use
    text: The use of the SSEN Distribution logo is strictly prohibited.
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
name: Scottish and Southern Electricity Networks
provenance_date: '2026-11-10'
provider_name: Scottish and Southern Electricity Networks
provider_slug: ssen
slug: ssen-eligibility
source_date: '2026-11-10'
source_filename: ssen-eligibility.yml
source_heading: Eligibility
source_page: https://data.ssen.co.uk/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Scottish and Southern Electricity Networks\naid: ssen\nurl: https://data.ssen.co.uk/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Logo use\n  text: The use of the SSEN Distribution logo is strictly prohibited.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/ssen/eligibility/ssen-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Scottish and Southern Electricity Networks's own page on 2026-11-10.
synthetic: false
tags:
- Energy
- United Kingdom
- Utilities
- Electricity
- Grid
- Distribution Network Operator
- Transmission
- Smart Metering
- Open Data
- Flexibility
- Renewables
- DER
---
