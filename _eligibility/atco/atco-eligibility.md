---
api_specs:
- filename: atco-query-api-openapi.yml
  format: yaml
  label: ATCO Query API
  slug: atco-query-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/atco/openapi/atco-query-api-openapi.yml
- filename: atco-service-api-openapi.yml
  format: yaml
  label: ATCO Service API
  slug: atco-service-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/atco/openapi/atco-service-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You may not access the ATCO website or use any information in those jurisdictions where it would be illegal.
  minimum_age:
    text: null
    value: null
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
name: ATCO
provenance_date: '2026-11-09'
provider_name: ATCO
provider_slug: atco
slug: atco-eligibility
source_date: '2026-11-09'
source_filename: atco-eligibility.yml
source_heading: Eligibility
source_page: https://www.atco.com/en-ca/terms-of-use.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ATCO\naid: atco\nurl: https://www.atco.com/en-ca/terms-of-use.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You may not access the ATCO website or use any information in those jurisdictions where it would be illegal.\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/atco/eligibility/atco-eligibility.yml
stated_fields:
- countries
summary_line: 1 quoted statement, read from ATCO's own page on 2026-11-09.
synthetic: false
tags:
- Energy
- Canada
- Utilities
- Electricity
- Gas
- Grid
- Distribution
- Transmission
- DER
- Solar
- Renewables
- Open Data
- Geospatial
- Alberta
---
