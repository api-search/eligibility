---
api_specs:
- filename: aisle-wedding-dress-codes-api-openapi.yml
  format: yaml
  label: Aisle Dress codes API
  slug: aisle-wedding-dress-codes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aisle-wedding/openapi/aisle-wedding-dress-codes-api-openapi.yml
- filename: aisle-wedding-events-api-openapi.yml
  format: yaml
  label: Aisle Events API
  slug: aisle-wedding-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aisle-wedding/openapi/aisle-wedding-events-api-openapi.yml
- filename: aisle-wedding-guest-access-api-openapi.yml
  format: yaml
  label: Aisle Guest access API
  slug: aisle-wedding-guest-access-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aisle-wedding/openapi/aisle-wedding-guest-access-api-openapi.yml
- filename: aisle-wedding-guest-content-api-openapi.yml
  format: yaml
  label: Aisle Guest content API
  slug: aisle-wedding-guest-content-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aisle-wedding/openapi/aisle-wedding-guest-content-api-openapi.yml
- filename: aisle-wedding-guests-api-openapi.yml
  format: yaml
  label: Aisle Guests API
  slug: aisle-wedding-guests-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aisle-wedding/openapi/aisle-wedding-guests-api-openapi.yml
- filename: aisle-wedding-media-api-openapi.yml
  format: yaml
  label: Aisle Media API
  slug: aisle-wedding-media-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aisle-wedding/openapi/aisle-wedding-media-api-openapi.yml
- filename: aisle-wedding-meta-api-openapi.yml
  format: yaml
  label: Aisle Meta API
  slug: aisle-wedding-meta-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aisle-wedding/openapi/aisle-wedding-meta-api-openapi.yml
- filename: aisle-wedding-parties-api-openapi.yml
  format: yaml
  label: Aisle Parties API
  slug: aisle-wedding-parties-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aisle-wedding/openapi/aisle-wedding-parties-api-openapi.yml
- filename: aisle-wedding-payments-api-openapi.yml
  format: yaml
  label: Aisle Payments API
  slug: aisle-wedding-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aisle-wedding/openapi/aisle-wedding-payments-api-openapi.yml
- filename: aisle-wedding-payouts-api-openapi.yml
  format: yaml
  label: Aisle Payouts API
  slug: aisle-wedding-payouts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aisle-wedding/openapi/aisle-wedding-payouts-api-openapi.yml
- filename: aisle-wedding-recommendations-api-openapi.yml
  format: yaml
  label: Aisle Recommendations API
  slug: aisle-wedding-recommendations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aisle-wedding/openapi/aisle-wedding-recommendations-api-openapi.yml
- filename: aisle-wedding-registry-api-openapi.yml
  format: yaml
  label: Aisle Registry API
  slug: aisle-wedding-registry-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aisle-wedding/openapi/aisle-wedding-registry-api-openapi.yml
- filename: aisle-wedding-rsvp-api-openapi.yml
  format: yaml
  label: Aisle RSVP API
  slug: aisle-wedding-rsvp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aisle-wedding/openapi/aisle-wedding-rsvp-api-openapi.yml
- filename: aisle-wedding-site-api-openapi.yml
  format: yaml
  label: Aisle Site API
  slug: aisle-wedding-site-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aisle-wedding/openapi/aisle-wedding-site-api-openapi.yml
- filename: aisle-wedding-statistics-api-openapi.yml
  format: yaml
  label: Aisle Statistics API
  slug: aisle-wedding-statistics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aisle-wedding/openapi/aisle-wedding-statistics-api-openapi.yml
- filename: aisle-wedding-stays-api-openapi.yml
  format: yaml
  label: Aisle Stays API
  slug: aisle-wedding-stays-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aisle-wedding/openapi/aisle-wedding-stays-api-openapi.yml
- filename: aisle-wedding-travel-api-openapi.yml
  format: yaml
  label: Aisle Travel API
  slug: aisle-wedding-travel-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aisle-wedding/openapi/aisle-wedding-travel-api-openapi.yml
- filename: aisle-wedding-wedding-api-openapi.yml
  format: yaml
  label: Aisle Wedding API
  slug: aisle-wedding-wedding-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aisle-wedding/openapi/aisle-wedding-wedding-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old and capable of forming a binding contract to use the Service.
    type: individual
  minimum_age:
    text: You must be at least 18 years old and capable of forming a binding contract to use the Service.
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
name: Aisle
provenance_date: '2026-11-09'
provider_name: Aisle
provider_slug: aisle-wedding
slug: aisle-wedding-eligibility
source_date: '2026-11-09'
source_filename: aisle-wedding-eligibility.yml
source_heading: Eligibility
source_page: https://aisle.wedding/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Aisle\naid: aisle-wedding\nurl: https://aisle.wedding/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old and capable of forming a binding contract to use the Service.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and capable of forming a binding contract to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/aisle-wedding/eligibility/aisle-wedding-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from Aisle's own page on 2026-11-09.
synthetic: false
tags:
- Wedding
- Planning
- Software-as-a-Service
- Marketplace
---
