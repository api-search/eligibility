---
api_specs:
- filename: packlink-clients-api-openapi.yml
  format: yaml
  label: Packlink Clients API
  slug: packlink-clients-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/packlink/openapi/packlink-clients-api-openapi.yml
- filename: packlink-customs-api-openapi.yml
  format: yaml
  label: Packlink Customs API
  slug: packlink-customs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/packlink/openapi/packlink-customs-api-openapi.yml
- filename: packlink-integrations-api-openapi.yml
  format: yaml
  label: Packlink Integrations API
  slug: packlink-integrations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/packlink/openapi/packlink-integrations-api-openapi.yml
- filename: packlink-locations-api-openapi.yml
  format: yaml
  label: Packlink Locations API
  slug: packlink-locations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/packlink/openapi/packlink-locations-api-openapi.yml
- filename: packlink-services-api-openapi.yml
  format: yaml
  label: Packlink Services API
  slug: packlink-services-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/packlink/openapi/packlink-services-api-openapi.yml
- filename: packlink-shipments-api-openapi.yml
  format: yaml
  label: Packlink Shipments API
  slug: packlink-shipments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/packlink/openapi/packlink-shipments-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 'User: Refers to any legal entity or entities without legal personality that operate for profit in the field of their commercial or business activity or (ii) self-employed worker'
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Prohibited items
    text: The articles appearing on the list of Prohibited Items cannot be sent through any Packlink service.
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
name: Packlink
provenance_date: '2026-11-10'
provider_name: Packlink
provider_slug: packlink
slug: packlink-eligibility
source_date: '2026-11-10'
source_filename: packlink-eligibility.yml
source_heading: Eligibility
source_page: https://www.packlink.com/en-GB/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Packlink\naid: packlink\nurl: https://www.packlink.com/en-GB/terms-and-conditions/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: 'User: Refers to any legal entity or entities without legal personality that operate for profit in the field\n    of their commercial or business activity or (ii) self-employed worker'\nrestricted_uses:\n- summary: Prohibited items\n  text: The articles appearing on the list of Prohibited Items cannot be sent through any Packlink service.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/packlink/eligibility/packlink-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Packlink's own page on 2026-11-10.
synthetic: false
tags:
- Company
- E-Commerce
- Shipping
- Logistics
- Parcel Delivery
- Carrier
- Fulfillment
---
