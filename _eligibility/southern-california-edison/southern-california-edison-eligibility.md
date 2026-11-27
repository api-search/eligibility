---
api_specs:
- filename: southern-california-edison-drpep-portal-api-openapi.yml
  format: yaml
  label: Southern California Edison DRPEP Portal API
  slug: southern-california-edison-drpep-portal-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/southern-california-edison/openapi/southern-california-edison-drpep-portal-api-openapi.yml
- filename: southern-california-edison-feature-services-api-openapi.yml
  format: yaml
  label: Southern California Edison Feature Services API
  slug: southern-california-edison-feature-services-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/southern-california-edison/openapi/southern-california-edison-feature-services-api-openapi.yml
- filename: southern-california-edison-query-api-openapi.yml
  format: yaml
  label: Southern California Edison Query API
  slug: southern-california-edison-query-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/southern-california-edison/openapi/southern-california-edison-query-api-openapi.yml
- filename: southern-california-edison-server-api-openapi.yml
  format: yaml
  label: Southern California Edison Server API
  slug: southern-california-edison-server-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/southern-california-edison/openapi/southern-california-edison-server-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: I declare under penalty of perjury under the laws of the State of California that I am the Customer of Record or an authorized user listed in SCE’s customer information system by the Customer of Record.
    type: individual
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: I understand that SCE reserves the right to verify any authorization request submitted before releasing information or taking any action on my behalf.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Southern California Edison
provenance_date: '2026-11-10'
provider_name: Southern California Edison
provider_slug: southern-california-edison
slug: southern-california-edison-eligibility
source_date: '2026-11-10'
source_filename: southern-california-edison-eligibility.yml
source_heading: Eligibility
source_page: https://www.sce.com/terms-conditions/customer-data-access-terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Southern California Edison\naid: southern-california-edison\nurl: https://www.sce.com/terms-conditions/customer-data-access-terms-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: I declare under penalty of perjury under the laws of the State of California that I am the Customer of Record\n    or an authorized user listed in SCE’s customer information system by the Customer of Record.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: I understand that SCE reserves the right to\
  \ verify any authorization request submitted before releasing\n    information or taking any action on my behalf.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/southern-california-edison/eligibility/southern-california-edison-eligibility.yml
stated_fields:
- entity_types
- verification
summary_line: 2 quoted statements, read from Southern California Edison's own page on 2026-11-10.
synthetic: false
tags:
- Energy
- United States
- Utilities
- Electricity
- Smart Metering
- Green Button
- Grid
- Demand Response
- Solar
- DER
- EV Charging
- California
---
