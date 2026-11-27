---
api_specs:
- filename: sentrial-events-api-openapi.yml
  format: yaml
  label: Sentrial Events API
  slug: sentrial-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sentrial/openapi/sentrial-events-api-openapi.yml
- filename: sentrial-sessions-api-openapi.yml
  format: yaml
  label: Sentrial Sessions API
  slug: sentrial-sessions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sentrial/openapi/sentrial-sessions-api-openapi.yml
claim_count: 1
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
  - summary: Illegal or unauthorized purpose
    text: Use the Service for any illegal or unauthorized purpose
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
name: Sentrial
provenance_date: '2026-11-10'
provider_name: Sentrial
provider_slug: sentrial
slug: sentrial-eligibility
source_date: '2026-11-10'
source_filename: sentrial-eligibility.yml
source_heading: Eligibility
source_page: https://www.sentrial.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Sentrial\naid: sentrial\nurl: https://www.sentrial.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Illegal or unauthorized purpose\n  text: Use the Service for any illegal or unauthorized purpose\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/sentrial/eligibility/sentrial-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Sentrial's own page on 2026-11-10.
synthetic: false
tags:
- Company
- AI Agents
- Observability
- Monitoring
- LLM
- Developer Tools
- Tracing
---
