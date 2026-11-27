---
api_specs:
- filename: actuallycare-com-v1-openapi.json
  format: json
  label: ActuallyCare API V1 API
  slug: actuallycare-api-v1-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/actuallycare-com/openapi/_original/actuallycare-com-v1-openapi.json
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Be at least 18 years old
    type: individual
  - text: Be a licensed real estate professional or work for a licensed real estate brokerage (for CareAgent and CareBroker accounts)
    type: business
  minimum_age:
    text: Be at least 18 years old
    value: '18'
  restricted_uses:
  - summary: Fair housing and real estate law
    text: Violate fair housing laws, anti-discrimination laws, or real estate regulations
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
name: ActuallyCare
provenance_date: '2026-11-09'
provider_name: ActuallyCare
provider_slug: actuallycare-com
slug: actuallycare-com-eligibility
source_date: '2026-11-09'
source_filename: actuallycare-com-eligibility.yml
source_heading: Eligibility
source_page: https://actuallycare.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ActuallyCare\naid: actuallycare-com\nurl: https://actuallycare.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Be at least 18 years old\n- type: business\n  text: Be a licensed real estate professional or work for a licensed real estate brokerage (for CareAgent and CareBroker\n    accounts)\nrestricted_uses:\n- summary: Fair housing and real estate law\n  text: Violate fair housing laws, anti-discrimination laws, or real estate regulations\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\n\
  minimum_age:\n  value: '18'\n  text: Be at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/actuallycare-com/eligibility/actuallycare-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from ActuallyCare's own page on 2026-11-09.
synthetic: false
tags:
- Real Estate CRM
- AI Assistant
- Deal Tracking
- Partner Network
---
