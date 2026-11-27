---
api_specs:
- filename: withlocals-availability-api-openapi.yml
  format: yaml
  label: Withlocals Availability API
  slug: withlocals-availability-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/withlocals/openapi/withlocals-availability-api-openapi.yml
- filename: withlocals-bookings-api-openapi.yml
  format: yaml
  label: Withlocals Bookings API
  slug: withlocals-bookings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/withlocals/openapi/withlocals-bookings-api-openapi.yml
- filename: withlocals-products-api-openapi.yml
  format: yaml
  label: Withlocals Products API
  slug: withlocals-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/withlocals/openapi/withlocals-products-api-openapi.yml
- filename: withlocals-supplier-api-openapi.yml
  format: yaml
  label: Withlocals Supplier API
  slug: withlocals-supplier-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/withlocals/openapi/withlocals-supplier-api-openapi.yml
- filename: withlocals-webhooks-api-openapi.yml
  format: yaml
  label: Withlocals Webhooks API
  slug: withlocals-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/withlocals/openapi/withlocals-webhooks-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Availability varies by destination
  entity_types:
  - text: Hosts are individuals or entities offering services through Withlocals.
    type: individual
  - text: Hosts are individuals or entities offering services through Withlocals.
    type: business
  minimum_age:
    text: For every booking, at least one person aged 18 or older must be present during the experience.
    value: '18'
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
name: Withlocals
provenance_date: '2026-11-10'
provider_name: Withlocals
provider_slug: withlocals
slug: withlocals-eligibility
source_date: '2026-11-10'
source_filename: withlocals-eligibility.yml
source_heading: Eligibility
source_page: https://www.withlocals.com/info/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Withlocals\naid: withlocals\nurl: https://www.withlocals.com/info/terms-and-conditions/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Availability varies by destination\nentity_types:\n- type: individual\n  text: Hosts are individuals or entities offering services through Withlocals.\n- type: business\n  text: Hosts are individuals or entities offering services through Withlocals.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: For every booking, at least one person aged 18 or older must\
  \ be present during the experience.\n"
source_yaml_url: https://artifacts.apis.io/withlocals/eligibility/withlocals-eligibility.yml
stated_fields:
- countries
- entity_types
- minimum_age
summary_line: 4 quoted statements, read from Withlocals's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Travel
- Tours
- Experience
- Tourism
- Marketplace
- Partner API
---
