---
api_specs:
- filename: thefork-customers-api-openapi.yml
  format: yaml
  label: TheFork Customers API
  slug: thefork-customers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thefork/openapi/thefork-customers-api-openapi.yml
- filename: thefork-orders-api-openapi.yml
  format: yaml
  label: TheFork Orders API
  slug: thefork-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thefork/openapi/thefork-orders-api-openapi.yml
- filename: thefork-reservations-api-openapi.yml
  format: yaml
  label: TheFork Reservations API
  slug: thefork-reservations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thefork/openapi/thefork-reservations-api-openapi.yml
- filename: thefork-reviews-api-openapi.yml
  format: yaml
  label: TheFork Reviews API
  slug: thefork-reviews-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thefork/openapi/thefork-reviews-api-openapi.yml
- filename: thefork-booking-flow-api-openapi.yml
  format: yaml
  label: TheFork Booking flow API
  slug: thefork-booking-flow-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thefork/openapi/thefork-booking-flow-api-openapi.yml
- filename: thefork-create-api-openapi.yml
  format: yaml
  label: TheFork Create API
  slug: thefork-create-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thefork/openapi/thefork-create-api-openapi.yml
- filename: thefork-data-api-openapi.yml
  format: yaml
  label: TheFork Data API
  slug: thefork-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thefork/openapi/thefork-data-api-openapi.yml
- filename: thefork-logo-api-openapi.yml
  format: yaml
  label: TheFork Logo API
  slug: thefork-logo-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thefork/openapi/thefork-logo-api-openapi.yml
- filename: thefork-phone-api-openapi.yml
  format: yaml
  label: TheFork Phone API
  slug: thefork-phone-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thefork/openapi/thefork-phone-api-openapi.yml
- filename: thefork-review-flow-api-openapi.yml
  format: yaml
  label: TheFork Review flow API
  slug: thefork-review-flow-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thefork/openapi/thefork-review-flow-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful or detrimental use
    text: you will not use the TheFork Partners API or the Data in any manner or for any purpose that may be contrary to any law or regulation
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: you must obtain Credentials from TheFork. These will be available via a dedicated developer portal where authorised developers can obtain their credentials
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: TheFork
provenance_date: '2026-11-10'
provider_name: TheFork
provider_slug: thefork
slug: thefork-eligibility
source_date: '2026-11-10'
source_filename: thefork-eligibility.yml
source_heading: Eligibility
source_page: https://docs.thefork.io/pdf/LaFourchette-Partners-API-Licence-2.pdf
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: TheFork\naid: thefork\nurl: https://docs.thefork.io/pdf/LaFourchette-Partners-API-Licence-2.pdf\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful or detrimental use\n  text: you will not use the TheFork Partners API or the Data in any manner or for any purpose that may be contrary\n    to any law or regulation\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: you must obtain Credentials from TheFork. These will be available via a dedicated developer portal where\n    authorised developers can obtain\
  \ their credentials\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/thefork/eligibility/thefork-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from TheFork's own page on 2026-11-10.
synthetic: false
tags:
- Restaurant
- Reservations
- Booking
- Dining
- Point-of-Sale
- Marketplace
---
