---
api_specs:
- filename: polly-ai-openapi-generated.yml
  format: yaml
  label: Polly API
  slug: polly-ai-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/polly-ai/openapi/_ae-authored/polly-ai-openapi-generated.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You may use the Services only if you are 16 years or older and capable of forming a binding contract with Subcurrent, Inc.
    value: '16'
  restricted_uses:
  - summary: Illegal or unauthorized purposes
    text: You may not use Polly for any illegal or unauthorized purpose.
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
name: Polly
provenance_date: '2026-11-10'
provider_name: Polly
provider_slug: polly-ai
slug: polly-ai-eligibility
source_date: '2026-11-10'
source_filename: polly-ai-eligibility.yml
source_heading: Eligibility
source_page: https://www.polly.ai/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Polly\naid: polly-ai\nurl: https://www.polly.ai/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Illegal or unauthorized purposes\n  text: You may not use Polly for any illegal or unauthorized purpose.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: You may use the Services only if you are 16 years or older and capable of forming a binding contract with\n    Subcurrent, Inc.\n"
source_yaml_url: https://artifacts.apis.io/polly-ai/eligibility/polly-ai-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Polly's own page on 2026-11-10.
synthetic: false
tags:
- Employee Engagement
- Surveys
- Polls
- Internal Communications
- Learning and Development
- Meetings
- HR Tools
- Integration
---
