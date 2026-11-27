---
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
  - summary: Acceptable use restrictions
    text: Activities that violate applicable laws or regulations.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Register only one primary account per individual, unless an additional business account is approved.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: ToAPIs
provenance_date: '2026-11-10'
provider_name: ToAPIs
provider_slug: toapis
slug: toapis-eligibility
source_date: '2026-11-10'
source_filename: toapis-eligibility.yml
source_heading: Eligibility
source_page: https://toapis.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ToAPIs\naid: toapis\nurl: https://toapis.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Acceptable use restrictions\n  text: Activities that violate applicable laws or regulations.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Register only one primary account per individual, unless an additional business account is approved.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/toapis/eligibility/toapis-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from ToAPIs's own page on 2026-11-10.
synthetic: false
tags:
- AI API
- LLM/AI gateway
- model aggregation
- OpenAI-Compatible
- Model Routing
- provider failover
- Text Generation
- Image Generation
- Video Generation
- Developer Tools
- A2A
---
