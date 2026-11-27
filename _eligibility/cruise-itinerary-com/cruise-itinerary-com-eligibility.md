---
api_specs:
- filename: cruise-itinerary-com-bulk-exports-api-openapi.yml
  format: yaml
  label: cruise-itinerary-com Bulk exports API
  slug: cruise-itinerary-com-bulk-exports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cruise-itinerary-com/openapi/cruise-itinerary-com-bulk-exports-api-openapi.yml
- filename: cruise-itinerary-com-changes-api-openapi.yml
  format: yaml
  label: cruise-itinerary-com Changes API
  slug: cruise-itinerary-com-changes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cruise-itinerary-com/openapi/cruise-itinerary-com-changes-api-openapi.yml
- filename: cruise-itinerary-com-cruise-itinerary-data-api-api-openapi.yml
  format: yaml
  label: cruise-itinerary-com Cruise Itinerary Data API
  slug: cruise-itinerary-com-cruise-itinerary-data-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cruise-itinerary-com/openapi/cruise-itinerary-com-cruise-itinerary-data-api-api-openapi.yml
- filename: cruise-itinerary-com-price-index-api-openapi.yml
  format: yaml
  label: cruise-itinerary-com Price index API
  slug: cruise-itinerary-com-price-index-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cruise-itinerary-com/openapi/cruise-itinerary-com-price-index-api-openapi.yml
- filename: cruise-itinerary-com-reference-data-api-openapi.yml
  format: yaml
  label: cruise-itinerary-com Reference data API
  slug: cruise-itinerary-com-reference-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cruise-itinerary-com/openapi/cruise-itinerary-com-reference-data-api-openapi.yml
- filename: cruise-itinerary-com-resolver-api-openapi.yml
  format: yaml
  label: cruise-itinerary-com Resolver API
  slug: cruise-itinerary-com-resolver-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cruise-itinerary-com/openapi/cruise-itinerary-com-resolver-api-openapi.yml
- filename: cruise-itinerary-com-sailings-api-openapi.yml
  format: yaml
  label: cruise-itinerary-com Sailings API
  slug: cruise-itinerary-com-sailings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cruise-itinerary-com/openapi/cruise-itinerary-com-sailings-api-openapi.yml
- filename: cruise-itinerary-com-service-api-openapi.yml
  format: yaml
  label: cruise-itinerary-com Service API
  slug: cruise-itinerary-com-service-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cruise-itinerary-com/openapi/cruise-itinerary-com-service-api-openapi.yml
- filename: cruise-itinerary-com-ships-and-ports-api-openapi.yml
  format: yaml
  label: cruise-itinerary-com Ships and ports API
  slug: cruise-itinerary-com-ships-and-ports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cruise-itinerary-com/openapi/cruise-itinerary-com-ships-and-ports-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18, or the age of majority where you live.
    type: individual
  - text: If you accept them for a company, you confirm you can bind that company.
    type: business
  minimum_age:
    text: You must be at least 18, or the age of majority where you live.
    value: '18'
  restricted_uses:
  - summary: No account sharing or limit avoidance
    text: Do not create accounts to avoid limits or to share a plan between unrelated parties.
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
name: cruise-itinerary-com
provenance_date: '2026-11-09'
provider_name: cruise-itinerary-com
provider_slug: cruise-itinerary-com
slug: cruise-itinerary-com-eligibility
source_date: '2026-11-09'
source_filename: cruise-itinerary-com-eligibility.yml
source_heading: Eligibility
source_page: https://cruise-itinerary.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: cruise-itinerary-com\naid: cruise-itinerary-com\nurl: https://cruise-itinerary.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18, or the age of majority where you live.\n- type: business\n  text: If you accept them for a company, you confirm you can bind that company.\nrestricted_uses:\n- summary: No account sharing or limit avoidance\n  text: Do not create accounts to avoid limits or to share a plan between unrelated parties.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text:\
  \ null\nminimum_age:\n  value: '18'\n  text: You must be at least 18, or the age of majority where you live.\n"
source_yaml_url: https://artifacts.apis.io/cruise-itinerary-com/eligibility/cruise-itinerary-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from cruise-itinerary-com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Travel
- Data
- Cruise
---
