---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: we only supply the Website for domestic or private use.
    type: individual
  - text: If you are a business, these terms and conditions shall be governed by and construed in accordance with English law.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Chatbot use limited to information requests
    text: You must not use the chatbot for any purpose other than to request information about us and our products and services.
  - summary: No commercial, business or resale use
    text: You agree not to use the Website for any commercial, business or resale purpose
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
name: National Grid Electricity Distribution
provenance_date: '2026-11-10'
provider_name: National Grid Electricity Distribution
provider_slug: national-grid-electricity-distribution
slug: national-grid-electricity-distribution-eligibility
source_date: '2026-11-10'
source_filename: national-grid-electricity-distribution-eligibility.yml
source_heading: Eligibility
source_page: https://customer.nationalgrid.co.uk/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: National Grid Electricity Distribution\naid: national-grid-electricity-distribution\nurl: https://customer.nationalgrid.co.uk/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: we only supply the Website for domestic or private use.\n- type: business\n  text: If you are a business, these terms and conditions shall be governed by and construed in accordance with\n    English law.\nrestricted_uses:\n- summary: Chatbot use limited to information requests\n  text: You must not use the chatbot for any purpose other than\
  \ to request information about us and our products\n    and services.\n- summary: No commercial, business or resale use\n  text: You agree not to use the Website for any commercial, business or resale purpose\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/national-grid-electricity-distribution/eligibility/national-grid-electricity-distribution-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from National Grid Electricity Distribution's own page on 2026-11-10.
synthetic: false
tags:
- Energy
- United Kingdom
- Utilities
- Electricity
- Grid
- Distribution Network
- Open Data
- Smart Metering
- DER
- Flexibility
- Renewables
---
