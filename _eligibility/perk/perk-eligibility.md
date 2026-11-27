---
api_specs:
- filename: perk-cost-centers-api-openapi.yml
  format: yaml
  label: Perk Cost centers API
  slug: perk-cost-centers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/perk/openapi/perk-cost-centers-api-openapi.yml
- filename: perk-custom-fields-api-openapi.yml
  format: yaml
  label: Perk Custom fields API
  slug: perk-custom-fields-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/perk/openapi/perk-custom-fields-api-openapi.yml
- filename: perk-bookings-api-openapi.yml
  format: yaml
  label: Perk Bookings API
  slug: perk-bookings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/perk/openapi/perk-bookings-api-openapi.yml
- filename: perk-companies-api-openapi.yml
  format: yaml
  label: Perk Companies API
  slug: perk-companies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/perk/openapi/perk-companies-api-openapi.yml
- filename: perk-invoices-api-openapi.yml
  format: yaml
  label: Perk Invoices API
  slug: perk-invoices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/perk/openapi/perk-invoices-api-openapi.yml
- filename: perk-profiles-api-openapi.yml
  format: yaml
  label: Perk Profiles API
  slug: perk-profiles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/perk/openapi/perk-profiles-api-openapi.yml
- filename: perk-schemas-api-openapi.yml
  format: yaml
  label: Perk Schemas API
  slug: perk-schemas-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/perk/openapi/perk-schemas-api-openapi.yml
- filename: perk-suppliers-api-openapi.yml
  format: yaml
  label: Perk Suppliers API
  slug: perk-suppliers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/perk/openapi/perk-suppliers-api-openapi.yml
- filename: perk-trips-api-openapi.yml
  format: yaml
  label: Perk Trips API
  slug: perk-trips-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/perk/openapi/perk-trips-api-openapi.yml
- filename: perk-users-api-openapi.yml
  format: yaml
  label: Perk Users API
  slug: perk-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/perk/openapi/perk-users-api-openapi.yml
- filename: perk-webhooks-api-openapi.yml
  format: yaml
  label: Perk Webhooks API
  slug: perk-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/perk/openapi/perk-webhooks-api-openapi.yml
- filename: perk-resource-types-api-openapi.yml
  format: yaml
  label: Perk Resource Types API
  slug: perk-resource-types-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/perk/openapi/perk-resource-types-api-openapi.yml
- filename: perk-service-provider-config-api-openapi.yml
  format: yaml
  label: Perk Service Provider Config API
  slug: perk-service-provider-config-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/perk/openapi/perk-service-provider-config-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are a Customer, your use of the Perk Platform shall be subject to our Service Terms
    type: business
  - text: If you are one of our third-party partners, the general conditions governing the nature of our partnership
    type: developer
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Personal use of AI client limited by employer
    text: If you use the Perk Platform as a user of one of our customers, you must only connect an AI Client where your organisation allows it.
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
name: Perk
provenance_date: '2026-11-10'
provider_name: Perk
provider_slug: perk
slug: perk-eligibility
source_date: '2026-11-10'
source_filename: perk-eligibility.yml
source_heading: Eligibility
source_page: https://developers.perk.com/docs/perk-marketplace-and-api-terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Perk\naid: perk\nurl: https://developers.perk.com/docs/perk-marketplace-and-api-terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are a Customer, your use of the Perk Platform shall be subject to our Service Terms\n- type: developer\n  text: If you are one of our third-party partners, the general conditions governing the nature of our partnership\nrestricted_uses:\n- summary: Personal use of AI client limited by employer\n  text: If you use the Perk Platform as a user of one of our customers, you must only connect an\
  \ AI Client where\n    your organisation allows it.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/perk/eligibility/perk-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Perk's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Corporate Travel
- Expense Management
- Spend Management
- Travel
- Invoices
- Fintech
- Software-as-a-Service
- Business Travel
- Travel Management
- Expenses
- Booking
---
