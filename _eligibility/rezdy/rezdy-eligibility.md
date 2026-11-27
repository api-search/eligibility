---
api_specs:
- filename: rezdy-availability-api-openapi.yml
  format: yaml
  label: Rezdy Availability API
  slug: rezdy-availability-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rezdy/openapi/rezdy-availability-api-openapi.yml
- filename: rezdy-bookings-api-openapi.yml
  format: yaml
  label: Rezdy Bookings API
  slug: rezdy-bookings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rezdy/openapi/rezdy-bookings-api-openapi.yml
- filename: rezdy-categories-api-openapi.yml
  format: yaml
  label: Rezdy Categories API
  slug: rezdy-categories-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rezdy/openapi/rezdy-categories-api-openapi.yml
- filename: rezdy-companies-api-openapi.yml
  format: yaml
  label: Rezdy Companies API
  slug: rezdy-companies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rezdy/openapi/rezdy-companies-api-openapi.yml
- filename: rezdy-manifest-api-openapi.yml
  format: yaml
  label: Rezdy Manifest API
  slug: rezdy-manifest-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rezdy/openapi/rezdy-manifest-api-openapi.yml
- filename: rezdy-products-api-openapi.yml
  format: yaml
  label: Rezdy Products API
  slug: rezdy-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rezdy/openapi/rezdy-products-api-openapi.yml
- filename: rezdy-resources-api-openapi.yml
  format: yaml
  label: Rezdy Resources API
  slug: rezdy-resources-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rezdy/openapi/rezdy-resources-api-openapi.yml
- filename: rezdy-vouchers-api-openapi.yml
  format: yaml
  label: Rezdy Vouchers API
  slug: rezdy-vouchers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rezdy/openapi/rezdy-vouchers-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You or your means you as an individual who accesses our Website, and where the context permits, includes any entity on whose behalf that person accesses our Website.
    type: individual
  - text: If you are agreeing to these Terms on behalf of a business entity, you represent to Rezdy that you have legal authority to bind that entity.
    type: business
  minimum_age:
    text: you warrant to us that you are over 18 years of age prior to any access or use of the Website
    value: '18'
  restricted_uses:
  - summary: business advertising without consent
    text: advertise or offer to sell or buy any goods or services for any business purpose, unless we expressly consent to such action
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
name: Rezdy
provenance_date: '2026-11-10'
provider_name: Rezdy
provider_slug: rezdy
slug: rezdy-eligibility
source_date: '2026-11-10'
source_filename: rezdy-eligibility.yml
source_heading: Eligibility
source_page: https://rezdy.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Rezdy\naid: rezdy\nurl: https://rezdy.com/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You or your means you as an individual who accesses our Website, and where the context permits, includes\n    any entity on whose behalf that person accesses our Website.\n- type: business\n  text: If you are agreeing to these Terms on behalf of a business entity, you represent to Rezdy that you have\n    legal authority to bind that entity.\nrestricted_uses:\n- summary: business advertising without consent\n  text: advertise or\
  \ offer to sell or buy any goods or services for any business purpose, unless we expressly consent\n    to such action\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you warrant to us that you are over 18 years of age prior to any access or use of the Website\n"
source_yaml_url: https://artifacts.apis.io/rezdy/eligibility/rezdy-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Rezdy's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Travel
- Booking
- Software-as-a-Service
- Tourism
---
