---
api_specs:
- filename: eventzilla-attendees-api-openapi.yml
  format: yaml
  label: Eventzilla Attendees API
  slug: eventzilla-attendees-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eventzilla/openapi/eventzilla-attendees-api-openapi.yml
- filename: eventzilla-categories-api-openapi.yml
  format: yaml
  label: Eventzilla Categories API
  slug: eventzilla-categories-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eventzilla/openapi/eventzilla-categories-api-openapi.yml
- filename: eventzilla-checkout-api-openapi.yml
  format: yaml
  label: Eventzilla Checkout API
  slug: eventzilla-checkout-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eventzilla/openapi/eventzilla-checkout-api-openapi.yml
- filename: eventzilla-events-api-openapi.yml
  format: yaml
  label: Eventzilla Events API
  slug: eventzilla-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eventzilla/openapi/eventzilla-events-api-openapi.yml
- filename: eventzilla-tickets-api-openapi.yml
  format: yaml
  label: Eventzilla Tickets API
  slug: eventzilla-tickets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eventzilla/openapi/eventzilla-tickets-api-openapi.yml
- filename: eventzilla-transactions-api-openapi.yml
  format: yaml
  label: Eventzilla Transactions API
  slug: eventzilla-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eventzilla/openapi/eventzilla-transactions-api-openapi.yml
- filename: eventzilla-users-api-openapi.yml
  format: yaml
  label: Eventzilla Users API
  slug: eventzilla-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eventzilla/openapi/eventzilla-users-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You are at least 13 years of age
    value: '13'
  restricted_uses:
  - summary: Illegal or unauthorized purposes
    text: You may not use the Service for any illegal or unauthorized purpose.
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
name: Eventzilla
provenance_date: '2026-11-09'
provider_name: Eventzilla
provider_slug: eventzilla
slug: eventzilla-eligibility
source_date: '2026-11-09'
source_filename: eventzilla-eligibility.yml
source_heading: Eligibility
source_page: https://www.eventzilla.net/terms-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Eventzilla\naid: eventzilla\nurl: https://www.eventzilla.net/terms-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Illegal or unauthorized purposes\n  text: You may not use the Service for any illegal or unauthorized purpose.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You are at least 13 years of age\n"
source_yaml_url: https://artifacts.apis.io/eventzilla/eligibility/eventzilla-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Eventzilla's own page on 2026-11-09.
synthetic: false
tags:
- Event
- Ticketing
- Registration
- Attendees
- Event Management
---
