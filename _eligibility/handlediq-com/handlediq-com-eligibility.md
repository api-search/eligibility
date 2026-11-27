---
api_specs:
- filename: handlediq-com-booking-status-api-openapi.yml
  format: yaml
  label: handlediq-com Booking Status API
  slug: handlediq-com-booking-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/handlediq-com/openapi/handlediq-com-booking-status-api-openapi.yml
- filename: handlediq-com-cancel-booking-api-openapi.yml
  format: yaml
  label: handlediq-com Cancel Booking API
  slug: handlediq-com-cancel-booking-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/handlediq-com/openapi/handlediq-com-cancel-booking-api-openapi.yml
- filename: handlediq-com-find-help-api-openapi.yml
  format: yaml
  label: handlediq-com Find Help API
  slug: handlediq-com-find-help-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/handlediq-com/openapi/handlediq-com-find-help-api-openapi.yml
- filename: handlediq-com-get-quote-api-openapi.yml
  format: yaml
  label: handlediq-com Get Quote API
  slug: handlediq-com-get-quote-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/handlediq-com/openapi/handlediq-com-get-quote-api-openapi.yml
- filename: handlediq-com-hold-time-api-openapi.yml
  format: yaml
  label: handlediq-com Hold Time API
  slug: handlediq-com-hold-time-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/handlediq-com/openapi/handlediq-com-hold-time-api-openapi.yml
- filename: handlediq-com-move-booking-api-openapi.yml
  format: yaml
  label: handlediq-com Move Booking API
  slug: handlediq-com-move-booking-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/handlediq-com/openapi/handlediq-com-move-booking-api-openapi.yml
- filename: handlediq-com-request-service-api-openapi.yml
  format: yaml
  label: handlediq-com Request Service API
  slug: handlediq-com-request-service-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/handlediq-com/openapi/handlediq-com-request-service-api-openapi.yml
- filename: handlediq-com-verify-record-api-openapi.yml
  format: yaml
  label: handlediq-com Verify Record API
  slug: handlediq-com-verify-record-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/handlediq-com/openapi/handlediq-com-verify-record-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: HandledIQ is for businesses, not for personal or household use.
    type: business
  minimum_age:
    text: confirms they are at least 18 and allowed to bind it.
    value: '18'
  restricted_uses:
  - summary: Business use only
    text: HandledIQ is for businesses, not for personal or household use.
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
name: handlediq-com
provenance_date: '2026-11-09'
provider_name: handlediq-com
provider_slug: handlediq-com
slug: handlediq-com-eligibility
source_date: '2026-11-09'
source_filename: handlediq-com-eligibility.yml
source_heading: Eligibility
source_page: https://app.handlediq.com/legal/terms.md
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: handlediq-com\naid: handlediq-com\nurl: https://app.handlediq.com/legal/terms.md\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: HandledIQ is for businesses, not for personal or household use.\nrestricted_uses:\n- summary: Business use only\n  text: HandledIQ is for businesses, not for personal or household use.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: confirms they are at least 18 and allowed to bind it.\n"
source_yaml_url: https://artifacts.apis.io/handlediq-com/eligibility/handlediq-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from handlediq-com's own page on 2026-11-09.
synthetic: false
tags:
- Field Service Management
- Software-as-a-Service
- Home Services
- Scheduling
- Payments
- Artificial Intelligence
---
