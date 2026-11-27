---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you use the Services on behalf of an entity, you represent and warrant that you have the authority to bind that entity
    type: business
  minimum_age:
    text: You may use the Services only if you are at least 16 years of age
    value: '16'
  restricted_uses:
  - summary: No residential vehicle use
    text: Sleeping in, residing in, or otherwise occupying any vehicle on the property—whether continuously or intermittently—is strictly prohibited, even if parking payment has been made.
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
name: AirGarage
provenance_date: '2026-11-09'
provider_name: AirGarage
provider_slug: airgarage
slug: airgarage-eligibility
source_date: '2026-11-09'
source_filename: airgarage-eligibility.yml
source_heading: Eligibility
source_page: https://www.airgarage.com/privacy#terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AirGarage\naid: airgarage\nurl: https://www.airgarage.com/privacy#terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you use the Services on behalf of an entity, you represent and warrant that you have the authority to\n    bind that entity\nrestricted_uses:\n- summary: No residential vehicle use\n  text: Sleeping in, residing in, or otherwise occupying any vehicle on the property—whether continuously or intermittently—is\n    strictly prohibited, even if parking payment has been made.\nverification:\n  kyc: null\n  kyb: null\n\
  \  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: You may use the Services only if you are at least 16 years of age\n"
source_yaml_url: https://artifacts.apis.io/airgarage/eligibility/airgarage-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from AirGarage's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Parking
- Parking Management
- Real Estate Technology
- PropTech
- Mobility
- Payments
- Enforcement
- Dynamic Pricing
---
