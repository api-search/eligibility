---
api_specs:
- filename: adaptlypost-com-api-openapi.json
  format: json
  label: AdaptlyPost Public API API
  slug: adaptlypost-public-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/adaptlypost-com/openapi/_original/adaptlypost-com-api-openapi.json
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you're signing up on behalf of a company, you're confirming you have the authority to do so.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Multiple accounts to abuse the system
    text: Create or operate multiple accounts to exploit free tiers, trials, promotional offers, or any other system features
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
name: AdaptlyPost
provenance_date: '2026-11-09'
provider_name: AdaptlyPost
provider_slug: adaptlypost-com
slug: adaptlypost-com-eligibility
source_date: '2026-11-09'
source_filename: adaptlypost-com-eligibility.yml
source_heading: Eligibility
source_page: https://adaptlypost.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AdaptlyPost\naid: adaptlypost-com\nurl: https://adaptlypost.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you're signing up on behalf of a company, you're confirming you have the authority to do so.\nrestricted_uses:\n- summary: Multiple accounts to abuse the system\n  text: Create or operate multiple accounts to exploit free tiers, trials, promotional offers, or any other system\n    features\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/adaptlypost-com/eligibility/adaptlypost-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from AdaptlyPost's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Social Media
- Scheduling
- AI Agents
---
