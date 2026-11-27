---
api_specs:
- filename: microsoft-bookings-solutions-bookingbusiness-api-openapi.yml
  format: yaml
  label: Microsoft Bookings Solutions.booking Business API
  slug: microsoft-bookings-solutions-bookingbusiness-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/microsoft-bookings/openapi/microsoft-bookings-solutions-bookingbusiness-api-openapi.yml
- filename: microsoft-bookings-solutions-bookingcurrency-api-openapi.yml
  format: yaml
  label: Microsoft Bookings Solutions.booking Currency API
  slug: microsoft-bookings-solutions-bookingcurrency-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/microsoft-bookings/openapi/microsoft-bookings-solutions-bookingcurrency-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Unless otherwise specified, the Services are for your personal and non-commercial use.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful or prohibited use
    text: you will not use the Services for any purpose that is unlawful or prohibited by these terms, conditions, and notices.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: If any of the Services requires you to open an account, you must complete the registration process by providing us with current, complete and accurate information as prompted by the applicable registration form.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Microsoft Bookings
provenance_date: '2026-11-10'
provider_name: Microsoft Bookings
provider_slug: microsoft-bookings
slug: microsoft-bookings-eligibility
source_date: '2026-11-10'
source_filename: microsoft-bookings-eligibility.yml
source_heading: Eligibility
source_page: https://www.microsoft.com/en-us/legal/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Microsoft Bookings\naid: microsoft-bookings\nurl: https://www.microsoft.com/en-us/legal/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Unless otherwise specified, the Services are for your personal and non-commercial use.\nrestricted_uses:\n- summary: Unlawful or prohibited use\n  text: you will not use the Services for any purpose that is unlawful or prohibited by these terms, conditions,\n    and notices.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: If any of the Services requires you\
  \ to open an account, you must complete the registration process by providing\n    us with current, complete and accurate information as prompted by the applicable registration form.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/microsoft-bookings/eligibility/microsoft-bookings-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from Microsoft Bookings's own page on 2026-11-10.
synthetic: false
tags:
- Booking
- Scheduling
- Appointments
- Microsoft Graph
- Calendar
- Microsoft 365
---
