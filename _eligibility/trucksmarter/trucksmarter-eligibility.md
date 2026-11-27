---
api_specs:
- filename: trucksmarter-loads-api-openapi.yml
  format: yaml
  label: TruckSmarter Loads API
  slug: trucksmarter-loads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trucksmarter/openapi/trucksmarter-loads-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Our Services are designed for use only by sole proprietors and other business entities for their internal business purposes.
    type: business
  minimum_age:
    text: You must be at least 18-years old to use the Services.
    value: '18'
  restricted_uses:
  - summary: No consumer or personal use
    text: You agree not to use our Services as a consumer for personal, family or household purposes.
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
name: TruckSmarter
provenance_date: '2026-11-10'
provider_name: TruckSmarter
provider_slug: trucksmarter
slug: trucksmarter-eligibility
source_date: '2026-11-10'
source_filename: trucksmarter-eligibility.yml
source_heading: Eligibility
source_page: https://www.trucksmarter.com/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: TruckSmarter\naid: trucksmarter\nurl: https://www.trucksmarter.com/legal/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Our Services are designed for use only by sole proprietors and other business entities for their internal\n    business purposes.\nrestricted_uses:\n- summary: No consumer or personal use\n  text: You agree not to use our Services as a consumer for personal, family or household purposes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: '18'\n  text: You must be at least 18-years old to use the Services.\n"
source_yaml_url: https://artifacts.apis.io/trucksmarter/eligibility/trucksmarter-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from TruckSmarter's own page on 2026-11-10.
synthetic: false
tags:
- Trucking
- Freight
- Logistics
- Load Board
- Transportation
- Dispatch
- Fuel
- Factoring
---
