---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You must be 13 or older and provide accurate information.
    value: '13'
  restricted_uses:
  - summary: Sensitive data
    text: collect payment card numbers, government ID numbers, health records, or other data we are not built to safeguard
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
name: Deoochform
provenance_date: '2026-11-09'
provider_name: Deoochform
provider_slug: deoochform-com
slug: deoochform-com-eligibility
source_date: '2026-11-09'
source_filename: deoochform-com-eligibility.yml
source_heading: Eligibility
source_page: https://deoochform.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Deoochform\naid: deoochform-com\nurl: https://deoochform.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Sensitive data\n  text: collect payment card numbers, government ID numbers, health records, or other data we are not built to safeguard\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You must be 13 or older and provide accurate information.\n"
source_yaml_url: https://artifacts.apis.io/deoochform-com/eligibility/deoochform-com-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Deoochform's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Forms
- Form Builder
- Surveys
- Artificial Intelligence
- MCP
- Payments
- Webhook
- No-Code
---
