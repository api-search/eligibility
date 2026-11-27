---
api_specs:
- filename: epcor-boundaries-api-openapi.yml
  format: yaml
  label: EPCOR Boundaries API
  slug: epcor-boundaries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/epcor/openapi/epcor-boundaries-api-openapi.yml
- filename: epcor-catalog-api-openapi.yml
  format: yaml
  label: EPCOR Catalog API
  slug: epcor-catalog-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/epcor/openapi/epcor-catalog-api-openapi.yml
- filename: epcor-infrastructure-api-openapi.yml
  format: yaml
  label: EPCOR Infrastructure API
  slug: epcor-infrastructure-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/epcor/openapi/epcor-infrastructure-api-openapi.yml
- filename: epcor-power-outages-api-openapi.yml
  format: yaml
  label: EPCOR Power Outages API
  slug: epcor-power-outages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/epcor/openapi/epcor-power-outages-api-openapi.yml
- filename: epcor-service-areas-api-openapi.yml
  format: yaml
  label: EPCOR Service Areas API
  slug: epcor-service-areas-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/epcor/openapi/epcor-service-areas-api-openapi.yml
- filename: epcor-us-water-outages-api-openapi.yml
  format: yaml
  label: EPCOR Us Water Outages API
  slug: epcor-us-water-outages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/epcor/openapi/epcor-us-water-outages-api-openapi.yml
- filename: epcor-water-outages-api-openapi.yml
  format: yaml
  label: EPCOR Water Outages API
  slug: epcor-water-outages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/epcor/openapi/epcor-water-outages-api-openapi.yml
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
  - summary: Misuse of secured sites and online services
    text: The user further acknowledges that any misuse that disrupts the normal use of the system, portals, or secured websites accessible through EPCOR websites is strictly prohibited.
  - summary: Unauthorized access to password protected areas
    text: Only authorized visitors may have access to and use of password protected and / or secure areas of this website.
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
name: EPCOR
provenance_date: '2026-11-09'
provider_name: EPCOR
provider_slug: epcor
slug: epcor-eligibility
source_date: '2026-11-09'
source_filename: epcor-eligibility.yml
source_heading: Eligibility
source_page: https://www.epcor.com/ca/en/about/policies/terms-of-use.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: EPCOR\naid: epcor\nurl: https://www.epcor.com/ca/en/about/policies/terms-of-use.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Misuse of secured sites and online services\n  text: The user further acknowledges that any misuse that disrupts the normal use of the system, portals, or secured\n    websites accessible through EPCOR websites is strictly prohibited.\n- summary: Unauthorized access to password protected areas\n  text: Only authorized visitors may have access to and use of password protected and / or secure areas\
  \ of this\n    website.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/epcor/eligibility/epcor-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 2 quoted statements, read from EPCOR's own page on 2026-11-09.
synthetic: false
tags:
- Energy
- Canada
- Utilities
- Electricity
- Natural Gas
- Water
- Green Button
- Smart Metering
- Grid
- Ontario
- Alberta
- Outages
- Geospatial
- Open Data
---
