---
api_specs:
- filename: securden-get-password-api-openapi.yml
  format: yaml
  label: Securden Get Password API
  slug: securden-get-password-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/securden/openapi/securden-get-password-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: either an individual or an entity
    type: individual
  - text: either an individual or an entity, and its Affiliates ("You" or "Company")
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Direct competitors
    text: license the Software if You are a direct competitor of Securden
  - summary: Computer-based services business
    text: use the Licensed Software in a computer-based services business
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
name: Securden
provenance_date: '2026-11-10'
provider_name: Securden
provider_slug: securden
slug: securden-eligibility
source_date: '2026-11-10'
source_filename: securden-eligibility.yml
source_heading: Eligibility
source_page: https://www.securden.com/end-user-license-agreement.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Securden\naid: securden\nurl: https://www.securden.com/end-user-license-agreement.html\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: either an individual or an entity\n- type: business\n  text: either an individual or an entity, and its Affiliates (\"You\" or \"Company\")\nrestricted_uses:\n- summary: Direct competitors\n  text: license the Software if You are a direct competitor of Securden\n- summary: Computer-based services business\n  text: use the Licensed Software in a computer-based services business\nverification:\n  kyc:\
  \ null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/securden/eligibility/securden-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from Securden's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Identity
- Security
- Privileged Access Management
- Password Management
- Secrets Management
- Endpoint Security
- DevOps
- AI Agent Security
---
