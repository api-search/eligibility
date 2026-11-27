---
api_specs:
- filename: transcript1-com-openapi.json
  format: json
  label: Transcript1 API
  slug: transcript1-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/transcript1-com/openapi/transcript1-com-openapi.json
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
  - summary: Illegal or infringing use
    text: Do not use the service to break the law, to infringe the rights of others, or to attack, overload or probe the service.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You need an account to use the service. Give accurate details and keep your sign-in methods to yourself.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: transcript1-com
provenance_date: '2026-11-10'
provider_name: transcript1-com
provider_slug: transcript1-com
slug: transcript1-com-eligibility
source_date: '2026-11-10'
source_filename: transcript1-com-eligibility.yml
source_heading: Eligibility
source_page: https://transcript1.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: transcript1-com\naid: transcript1-com\nurl: https://transcript1.com/legal/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Illegal or infringing use\n  text: Do not use the service to break the law, to infringe the rights of others, or to attack, overload or probe\n    the service.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You need an account to use the service. Give accurate details and keep your sign-in methods to yourself.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/transcript1-com/eligibility/transcript1-com-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from transcript1-com's own page on 2026-11-10.
synthetic: false
tags:
- Audio
- Video
- Transcription
- MCP
---
