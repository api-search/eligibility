---
api_specs:
- filename: antalyatransfers-co-fx-api-openapi.yml
  format: yaml
  label: AntalyaTransfers.co Fx API
  slug: antalyatransfers-co-fx-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/antalyatransfers-co/openapi/antalyatransfers-co-fx-api-openapi.yml
- filename: antalyatransfers-co-locations-api-openapi.yml
  format: yaml
  label: AntalyaTransfers.co Locations API
  slug: antalyatransfers-co-locations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/antalyatransfers-co/openapi/antalyatransfers-co-locations-api-openapi.yml
- filename: antalyatransfers-co-pricing-api-openapi.yml
  format: yaml
  label: AntalyaTransfers.co Pricing API
  slug: antalyatransfers-co-pricing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/antalyatransfers-co/openapi/antalyatransfers-co-pricing-api-openapi.yml
- filename: antalyatransfers-co-status-api-openapi.yml
  format: yaml
  label: AntalyaTransfers.co Status API
  slug: antalyatransfers-co-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/antalyatransfers-co/openapi/antalyatransfers-co-status-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - TR
    text: 'Service area: Antalya, Turkey'
  entity_types:
  - text: any individual ("you", "Passenger") who uses this website or the booking service
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Prohibited items in transfers
    text: Not transport prohibited items (weapons, controlled substances, etc.)
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
name: AntalyaTransfers.co
provenance_date: '2026-11-09'
provider_name: AntalyaTransfers.co
provider_slug: antalyatransfers-co
slug: antalyatransfers-co-eligibility
source_date: '2026-11-09'
source_filename: antalyatransfers-co-eligibility.yml
source_heading: Eligibility
source_page: https://antalyatransfers.co/en/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AntalyaTransfers.co\naid: antalyatransfers-co\nurl: https://antalyatransfers.co/en/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - TR\n  excluded: []\n  text: 'Service area: Antalya, Turkey'\nentity_types:\n- type: individual\n  text: any individual (\"you\", \"Passenger\") who uses this website or the booking service\nrestricted_uses:\n- summary: Prohibited items in transfers\n  text: Not transport prohibited items (weapons, controlled substances, etc.)\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/antalyatransfers-co/eligibility/antalyatransfers-co-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from AntalyaTransfers.co's own page on 2026-11-09.
synthetic: false
tags:
- Transportation
- Travel
- Booking
- Turkey
- Taxi
---
