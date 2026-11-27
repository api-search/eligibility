---
api_specs:
- filename: 5arz-com-api-openapi.json
  format: json
  label: 5arz Proof-of-Human API API
  slug: 5arz-proof-of-human-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/5arz-com/openapi/_original/5arz-com-api-openapi.json
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: You are a US resident in a state where 5arz is currently authorized to operate.
  entity_types:
  - text: You are at least 18 years old.
    type: individual
  minimum_age:
    text: You are at least 18 years old.
    value: '18'
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: You can pass our identity verification (Stripe Identity).
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: 5arz
provenance_date: '2026-11-09'
provider_name: 5arz
provider_slug: 5arz-com
slug: 5arz-com-eligibility
source_date: '2026-11-09'
source_filename: 5arz-com-eligibility.yml
source_heading: Eligibility
source_page: https://5arz.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: 5arz\naid: 5arz-com\nurl: https://5arz.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: You are a US resident in a state where 5arz is currently authorized to operate.\nentity_types:\n- type: individual\n  text: You are at least 18 years old.\nrestricted_uses: []\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: You can pass our identity verification (Stripe Identity).\nminimum_age:\n  value: '18'\n  text: You are at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/5arz-com/eligibility/5arz-com-eligibility.yml
stated_fields:
- countries
- entity_types
- verification
- minimum_age
summary_line: 4 quoted statements, read from 5arz's own page on 2026-11-09.
synthetic: false
tags:
- Human Verification
- Artificial Intelligence
- Privacy
- Developer Tools
- Authentication
---
