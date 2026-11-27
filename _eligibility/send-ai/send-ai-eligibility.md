---
api_specs:
- filename: send-ai-openapi-generated.yml
  format: yaml
  label: Send AI API
  slug: send-ai-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/send-ai/openapi/_ae-authored/send-ai-openapi-generated.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: solely for Customer's internal business purposes
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No resale or sublicensing
    text: Make the Service available to anyone other than Authorized Users
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
name: Send AI
provenance_date: '2026-11-10'
provider_name: Send AI
provider_slug: send-ai
slug: send-ai-eligibility
source_date: '2026-11-10'
source_filename: send-ai-eligibility.yml
source_heading: Eligibility
source_page: https://www.send.ai/legal/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Send AI\naid: send-ai\nurl: https://www.send.ai/legal/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: solely for Customer's internal business purposes\nrestricted_uses:\n- summary: No resale or sublicensing\n  text: Make the Service available to anyone other than Authorized Users\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/send-ai/eligibility/send-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Send AI's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Document Processing
- EDI
- Supply Chain
- Integration
---
