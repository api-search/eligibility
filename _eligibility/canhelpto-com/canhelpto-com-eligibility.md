---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you act for a company, you confirm you may bind it.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unsolicited messages, unlawful content
    text: You will not use the Service to send unsolicited messages, to collect data you have no right to collect, to store content that is unlawful, infringing or malicious
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You sign in with a one-time code sent to your email or phone.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: canhelpto
provenance_date: '2026-11-09'
provider_name: canhelpto
provider_slug: canhelpto-com
slug: canhelpto-com-eligibility
source_date: '2026-11-09'
source_filename: canhelpto-com-eligibility.yml
source_heading: Eligibility
source_page: https://canhelpto.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: canhelpto\naid: canhelpto-com\nurl: https://canhelpto.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you act for a company, you confirm you may bind it.\nrestricted_uses:\n- summary: Unsolicited messages, unlawful content\n  text: You will not use the Service to send unsolicited messages, to collect data you have no right to collect,\n    to store content that is unlawful, infringing or malicious\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You sign in with a one-time code sent to your email\
  \ or phone.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/canhelpto-com/eligibility/canhelpto-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from canhelpto's own page on 2026-11-09.
synthetic: false
tags:
- Customer Service
- AI Integration
- MCP Server
- Help Desk
- Automation
---
