---
api_specs:
- filename: tourscanner-ai-tourscanner-api-openapi.yml
  format: yaml
  label: TourScanner API
  slug: tourscanner-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tourscanner-ai/openapi/tourscanner-ai-tourscanner-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you use the Service for a company, you confirm that you can bind that company.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No unlawful, fraudulent or misleading activity
    text: Do not use the Service for unlawful, fraudulent or misleading activity, including fake bookings.
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
name: TourScanner AI
provenance_date: '2026-11-10'
provider_name: TourScanner AI
provider_slug: tourscanner-ai
slug: tourscanner-ai-eligibility
source_date: '2026-11-10'
source_filename: tourscanner-ai-eligibility.yml
source_heading: Eligibility
source_page: https://tourscanner.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: TourScanner AI\naid: tourscanner-ai\nurl: https://tourscanner.ai/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you use the Service for a company, you confirm that you can bind that company.\nrestricted_uses:\n- summary: No unlawful, fraudulent or misleading activity\n  text: Do not use the Service for unlawful, fraudulent or misleading activity, including fake bookings.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/tourscanner-ai/eligibility/tourscanner-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from TourScanner AI's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Tours
- Activities
- Booking
---
