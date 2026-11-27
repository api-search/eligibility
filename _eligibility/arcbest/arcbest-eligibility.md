---
api_specs:
- filename: arcbest-pickups-api-openapi.yml
  format: yaml
  label: ArcBest Pickups API
  slug: arcbest-pickups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arcbest/openapi/arcbest-pickups-api-openapi.yml
- filename: arcbest-rates-api-openapi.yml
  format: yaml
  label: ArcBest Rates API
  slug: arcbest-rates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arcbest/openapi/arcbest-rates-api-openapi.yml
- filename: arcbest-shipments-api-openapi.yml
  format: yaml
  label: ArcBest Shipments API
  slug: arcbest-shipments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arcbest/openapi/arcbest-shipments-api-openapi.yml
- filename: arcbest-tracking-api-openapi.yml
  format: yaml
  label: ArcBest Tracking API
  slug: arcbest-tracking-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arcbest/openapi/arcbest-tracking-api-openapi.yml
- filename: arcbest-authorize-api-openapi.yml
  format: yaml
  label: ArcBest Authorize API
  slug: arcbest-authorize-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arcbest/openapi/arcbest-authorize-api-openapi.yml
- filename: arcbest-booking-api-openapi.yml
  format: yaml
  label: ArcBest Booking API
  slug: arcbest-booking-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arcbest/openapi/arcbest-booking-api-openapi.yml
- filename: arcbest-order-api-openapi.yml
  format: yaml
  label: ArcBest Order API
  slug: arcbest-order-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arcbest/openapi/arcbest-order-api-openapi.yml
- filename: arcbest-quote-api-openapi.yml
  format: yaml
  label: ArcBest Quote API
  slug: arcbest-quote-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arcbest/openapi/arcbest-quote-api-openapi.yml
- filename: arcbest-quotes-api-openapi.yml
  format: yaml
  label: ArcBest Quotes API
  slug: arcbest-quotes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arcbest/openapi/arcbest-quotes-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: 'Export restriction: You acknowledge and agree that You will not export or import any Content to any country to which export or import is restricted under United States law, and that You are not a national of any such country.'
  entity_types:
  - text: By using this Website, you represent and warrant that You can legally bind yourself to this agreement or You have the proper authority to bind the entity You represent.
    type: business
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
name: ArcBest
provenance_date: '2026-11-09'
provider_name: ArcBest
provider_slug: arcbest
slug: arcbest-eligibility
source_date: '2026-11-09'
source_filename: arcbest-eligibility.yml
source_heading: Eligibility
source_page: https://arcb.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ArcBest\naid: arcbest\nurl: https://arcb.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: 'Export restriction: You acknowledge and agree that You will not export or import any Content to any country\n    to which export or import is restricted under United States law, and that You are not a national of any such\n    country.'\nentity_types:\n- type: business\n  text: By using this Website, you represent and warrant that You can legally bind yourself to this agreement or\n    You have the proper authority to bind the entity You represent.\nrestricted_uses: []\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/arcbest/eligibility/arcbest-eligibility.yml
stated_fields:
- countries
- entity_types
summary_line: 2 quoted statements, read from ArcBest's own page on 2026-11-09.
synthetic: false
tags:
- Logistics
- Freight
- LTL
- Supply Chain
- Shipping
- Transportation
- Expedite
- Truckload
- EDI
- Bill of Lading
- Rate Quote
- Shipment Tracking
---
