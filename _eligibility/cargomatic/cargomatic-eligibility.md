---
api_specs:
- filename: cargomatic-authorization-api-openapi.yml
  format: yaml
  label: Cargomatic Authorization API
  slug: cargomatic-authorization-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cargomatic/openapi/cargomatic-authorization-api-openapi.yml
- filename: cargomatic-carrier-api-openapi.yml
  format: yaml
  label: Cargomatic Carrier API
  slug: cargomatic-carrier-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cargomatic/openapi/cargomatic-carrier-api-openapi.yml
- filename: cargomatic-document-api-openapi.yml
  format: yaml
  label: Cargomatic Document API
  slug: cargomatic-document-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cargomatic/openapi/cargomatic-document-api-openapi.yml
- filename: cargomatic-shipper-api-openapi.yml
  format: yaml
  label: Cargomatic Shipper API
  slug: cargomatic-shipper-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cargomatic/openapi/cargomatic-shipper-api-openapi.yml
- filename: cargomatic-stops-api-openapi.yml
  format: yaml
  label: Cargomatic Stops API
  slug: cargomatic-stops-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cargomatic/openapi/cargomatic-stops-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: connects motor carrier businesses (“Carriers”)
    type: business
  minimum_age:
    text: YOU MAY NOT ACCESS OR USE THE SERVICE OR ACCEPT THIS AGREEMENT IF YOU ARE NOT AT LEAST 18 YEARS OLD.
    value: '18'
  restricted_uses:
  - summary: Prohibited shipment items
    text: Shippers shall not use the Service to ship the below items
  - summary: Acceptable use restrictions
    text: you agree not to use the Service to collect, upload, transmit, display, or distribute any User Content
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Shippers must provide a valid credit card and billing address or ACH information. Carriers must provide valid license information.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Cargomatic
provenance_date: '2026-11-09'
provider_name: Cargomatic
provider_slug: cargomatic
slug: cargomatic-eligibility
source_date: '2026-11-09'
source_filename: cargomatic-eligibility.yml
source_heading: Eligibility
source_page: https://cargomatic.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cargomatic\naid: cargomatic\nurl: https://cargomatic.com/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: connects motor carrier businesses (“Carriers”)\nrestricted_uses:\n- summary: Prohibited shipment items\n  text: Shippers shall not use the Service to ship the below items\n- summary: Acceptable use restrictions\n  text: you agree not to use the Service to collect, upload, transmit, display, or distribute any User Content\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text:\
  \ Shippers must provide a valid credit card and billing address or ACH information. Carriers must provide\n    valid license information.\nminimum_age:\n  value: '18'\n  text: YOU MAY NOT ACCESS OR USE THE SERVICE OR ACCEPT THIS AGREEMENT IF YOU ARE NOT AT LEAST 18 YEARS OLD.\n"
source_yaml_url: https://artifacts.apis.io/cargomatic/eligibility/cargomatic-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Cargomatic's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Logistics
- Freight
- Drayage
- Transportation
- Supply Chain
- Shipping
- Trucking
- Marketplace
- Intermodal
---
