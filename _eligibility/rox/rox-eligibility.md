---
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
  - summary: Unsolicited bulk and robocall messaging
    text: not use the Services to send unsolicited bulk messages or to place calls using artificial or prerecorded voice
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
name: Rox
provenance_date: '2026-11-10'
provider_name: Rox
provider_slug: rox
slug: rox-eligibility
source_date: '2026-11-10'
source_filename: rox-eligibility.yml
source_heading: Eligibility
source_page: https://www.rox.com/legal/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Rox\naid: rox\nurl: https://www.rox.com/legal/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unsolicited bulk and robocall messaging\n  text: not use the Services to send unsolicited bulk messages or to place calls using artificial or prerecorded\n    voice\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/rox/eligibility/rox-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Rox's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- AI Agents
- Sales
- Revenue Operations
- Go-To-Market
- CRM
- Sales Intelligence
- Enterprise
- Revenue Intelligence
---
