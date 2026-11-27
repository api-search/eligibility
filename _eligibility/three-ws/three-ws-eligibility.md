---
api_specs:
- filename: openapi.json
  format: json
  label: three.ws API
  slug: main-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/three-ws/openapi.json
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You may not use the Service if you are located in, or are a resident or national of, any jurisdiction subject to comprehensive sanctions by the United States
  entity_types:
  - text: You must be at least 13 years old to use the Service. If you are under 18, you represent that a parent or legal guardian has reviewed and agreed to these Terms on your behalf
    type: individual
  minimum_age:
    text: You must be at least 13 years old to use the Service.
    value: '13'
  restricted_uses:
  - summary: Real-Funds Features
    text: You must be at least 18 years old, and of legal age in your jurisdiction, to use any Real-Funds Feature
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
name: three-ws
provenance_date: '2026-11-10'
provider_name: three-ws
provider_slug: three-ws
slug: three-ws-eligibility
source_date: '2026-11-10'
source_filename: three-ws-eligibility.yml
source_heading: Eligibility
source_page: https://three.ws/legal/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: three-ws\naid: three-ws\nurl: https://three.ws/legal/tos\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You may not use the Service if you are located in, or are a resident or national of, any jurisdiction subject\n    to comprehensive sanctions by the United States\nentity_types:\n- type: individual\n  text: You must be at least 13 years old to use the Service. If you are under 18, you represent that a parent or\n    legal guardian has reviewed and agreed to these Terms on your behalf\nrestricted_uses:\n- summary: Real-Funds Features\n  text: You must be at least 18 years old,\
  \ and of legal age in your jurisdiction, to use any Real-Funds Feature\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You must be at least 13 years old to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/three-ws/eligibility/three-ws-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from three-ws's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- 3D
- Agents
- Web3
---
