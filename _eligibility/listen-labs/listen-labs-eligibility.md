---
api_specs:
- filename: listen-labs-public-api-openapi.yml
  format: yaml
  label: Listen Labs Public API
  slug: listen-labs-public-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/listen-labs/openapi/listen-labs-public-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old to use the Services. By creating an account, you represent that you are at least 18
    type: individual
  minimum_age:
    text: You must be at least 18 years old to use the Services.
    value: '18'
  restricted_uses:
  - summary: Fraudulent or illegal purpose
    text: Use the Services for any fraudulent or illegal purpose
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
name: Listen Labs
provenance_date: '2026-11-09'
provider_name: Listen Labs
provider_slug: listen-labs
slug: listen-labs-eligibility
source_date: '2026-11-09'
source_filename: listen-labs-eligibility.yml
source_heading: Eligibility
source_page: https://listenlabs.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Listen Labs\naid: listen-labs\nurl: https://listenlabs.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old to use the Services. By creating an account, you represent that you are\n    at least 18\nrestricted_uses:\n- summary: Fraudulent or illegal purpose\n  text: Use the Services for any fraudulent or illegal purpose\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to use the Services.\n"
source_yaml_url: https://artifacts.apis.io/listen-labs/eligibility/listen-labs-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Listen Labs's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Market Research
- Customer Research
- User Interviews
- Surveys
- Qualitative Research
- Voice AI
- Insights
- Agents
---
