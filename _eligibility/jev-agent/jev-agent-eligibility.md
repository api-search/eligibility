---
api_specs:
- filename: jev-agent-openapi-generated.yml
  format: yaml
  label: Jev Agent (Jagent) API
  slug: jev-agent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jev-agent/openapi/_ae-authored/jev-agent-openapi-generated.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Other people's personal data
    text: Do not send other people's personal data through the API.
  verification:
    approval_required: false
    kyb: null
    kyc: null
    text: Anyone can get a key. It is 5 credits a month, free, with no card and no waitlist.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Jev Agent (Jagent)
provenance_date: '2026-11-09'
provider_name: Jev Agent (Jagent)
provider_slug: jev-agent
slug: jev-agent-eligibility
source_date: '2026-11-09'
source_filename: jev-agent-eligibility.yml
source_heading: Eligibility
source_page: https://jev-agent.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Jev Agent (Jagent)\naid: jev-agent\nurl: https://jev-agent.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Other people's personal data\n  text: Do not send other people's personal data through the API.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: false\n  text: Anyone can get a key. It is 5 credits a month, free, with no card and no waitlist.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/jev-agent/eligibility/jev-agent-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from Jev Agent (Jagent)'s own page on 2026-11-09.
synthetic: false
tags:
- AI API
- Classification
- Token Billing
- Developer Tools
---
