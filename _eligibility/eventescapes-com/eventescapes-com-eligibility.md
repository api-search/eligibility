---
api_specs:
- filename: eventescapes-com-events-api-openapi.yml
  format: yaml
  label: Event Escapes Events API
  slug: eventescapes-com-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eventescapes-com/openapi/eventescapes-com-events-api-openapi.yml
- filename: eventescapes-com-experiences-api-openapi.yml
  format: yaml
  label: Event Escapes Experiences API
  slug: eventescapes-com-experiences-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eventescapes-com/openapi/eventescapes-com-experiences-api-openapi.yml
- filename: eventescapes-com-packages-api-openapi.yml
  format: yaml
  label: Event Escapes Packages API
  slug: eventescapes-com-packages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eventescapes-com/openapi/eventescapes-com-packages-api-openapi.yml
- filename: eventescapes-com-payment-links-api-openapi.yml
  format: yaml
  label: Event Escapes Payment Links API
  slug: eventescapes-com-payment-links-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eventescapes-com/openapi/eventescapes-com-payment-links-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old and have legal capacity to enter into a binding contract to use our services.
    type: individual
  minimum_age:
    text: You must be at least 18 years old and have legal capacity to enter into a binding contract to use our services.
    value: '18'
  restricted_uses:
  - summary: Fraudulent or speculative bookings
    text: not to make speculative, false, or fraudulent bookings, or bookings in anticipation of demand.
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
name: Event Escapes
provenance_date: '2026-11-09'
provider_name: Event Escapes
provider_slug: eventescapes-com
slug: eventescapes-com-eligibility
source_date: '2026-11-09'
source_filename: eventescapes-com-eligibility.yml
source_heading: Eligibility
source_page: https://eventescapes.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Event Escapes\naid: eventescapes-com\nurl: https://eventescapes.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old and have legal capacity to enter into a binding contract to use our services.\nrestricted_uses:\n- summary: Fraudulent or speculative bookings\n  text: not to make speculative, false, or fraudulent bookings, or bookings in anticipation of demand.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at\
  \ least 18 years old and have legal capacity to enter into a binding contract to use our services.\n"
source_yaml_url: https://artifacts.apis.io/eventescapes-com/eligibility/eventescapes-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Event Escapes's own page on 2026-11-09.
synthetic: false
tags:
- Travel
- Event
- Ticketing
- Hotels
- Sports
---
