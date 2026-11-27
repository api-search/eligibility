---
api_specs:
- filename: marubox-account-api-openapi.yml
  format: yaml
  label: Business Box Account API
  slug: marubox-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/marubox/openapi/marubox-account-api-openapi.yml
- filename: marubox-bookings-api-openapi.yml
  format: yaml
  label: Business Box Bookings API
  slug: marubox-bookings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/marubox/openapi/marubox-bookings-api-openapi.yml
- filename: marubox-event-types-api-openapi.yml
  format: yaml
  label: Business Box Event types API
  slug: marubox-event-types-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/marubox/openapi/marubox-event-types-api-openapi.yml
- filename: marubox-invites-api-openapi.yml
  format: yaml
  label: Business Box Invites API
  slug: marubox-invites-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/marubox/openapi/marubox-invites-api-openapi.yml
- filename: marubox-webhooks-api-openapi.yml
  format: yaml
  label: Business Box Webhooks API
  slug: marubox-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/marubox/openapi/marubox-webhooks-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be able to enter into a contract
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful or misleading use
    text: Do not use the service to break the law
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
name: Business Box
provenance_date: '2026-11-10'
provider_name: Business Box
provider_slug: marubox
slug: marubox-eligibility
source_date: '2026-11-10'
source_filename: marubox-eligibility.yml
source_heading: Eligibility
source_page: https://marubox.jp/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Business Box\naid: marubox\nurl: https://marubox.jp/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be able to enter into a contract\nrestricted_uses:\n- summary: Unlawful or misleading use\n  text: Do not use the service to break the law\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/marubox/eligibility/marubox-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Business Box's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Booking
- Payments
- Calendar
- Japan
---
