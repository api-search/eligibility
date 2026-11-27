---
api_specs:
- filename: lyft-concierge-rides-api-openapi.yml
  format: yaml
  label: lyft Concierge Rides API
  slug: lyft-concierge-rides-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lyft/openapi/lyft-concierge-rides-api-openapi.yml
- filename: lyft-cost-estimates-api-openapi.yml
  format: yaml
  label: lyft Cost Estimates API
  slug: lyft-cost-estimates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lyft/openapi/lyft-cost-estimates-api-openapi.yml
- filename: lyft-drivers-api-openapi.yml
  format: yaml
  label: lyft Drivers API
  slug: lyft-drivers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lyft/openapi/lyft-drivers-api-openapi.yml
- filename: lyft-eta-api-openapi.yml
  format: yaml
  label: lyft ETA API
  slug: lyft-eta-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lyft/openapi/lyft-eta-api-openapi.yml
- filename: lyft-profile-api-openapi.yml
  format: yaml
  label: lyft Profile API
  slug: lyft-profile-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lyft/openapi/lyft-profile-api-openapi.yml
- filename: lyft-ride-types-api-openapi.yml
  format: yaml
  label: lyft Ride Types API
  slug: lyft-ride-types-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lyft/openapi/lyft-ride-types-api-openapi.yml
- filename: lyft-rides-api-openapi.yml
  format: yaml
  label: lyft Rides API
  slug: lyft-rides-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lyft/openapi/lyft-rides-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: By becoming a User, you represent and warrant that you are at least 18 years old.
    type: individual
  minimum_age:
    text: By becoming a User, you represent and warrant that you are at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: Use on behalf of third parties
    text: you may not use your User account on behalf of any third party, except as otherwise expressly permitted by Lyft
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
name: Lyft
provenance_date: '2026-11-10'
provider_name: Lyft
provider_slug: lyft
slug: lyft-eligibility
source_date: '2026-11-10'
source_filename: lyft-eligibility.yml
source_heading: Eligibility
source_page: https://www.lyft.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Lyft\naid: lyft\nurl: https://www.lyft.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: By becoming a User, you represent and warrant that you are at least 18 years old.\nrestricted_uses:\n- summary: Use on behalf of third parties\n  text: you may not use your User account on behalf of any third party, except as otherwise expressly permitted\n    by Lyft\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: By becoming a User, you represent\
  \ and warrant that you are at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/lyft/eligibility/lyft-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Lyft's own page on 2026-11-10.
synthetic: false
tags:
- Transportation
- Mobility
- Ride Hailing
- Micromobility
- Bike Share
- Scooters
- GBFS
- Logistics
- Travel
---
