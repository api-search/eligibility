---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: you, whether personally or on behalf of an entity
    type: individual
  - text: Legal Terms constitute a legally binding agreement made between you, whether personally or on behalf of an entity
    type: business
  minimum_age:
    text: You are not a minor in the jurisdiction in which you reside.
    value: null
  restricted_uses:
  - summary: No automated access
    text: You will not access the Services through automated or non-human means, whether through a bot, script, or otherwise.
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
name: Take2.ai
provenance_date: '2026-11-10'
provider_name: Take2.ai
provider_slug: take2ai
slug: take2ai-eligibility
source_date: '2026-11-10'
source_filename: take2ai-eligibility.yml
source_heading: Eligibility
source_page: https://www.take2.ai/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Take2.ai\naid: take2ai\nurl: https://www.take2.ai/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: you, whether personally or on behalf of an entity\n- type: business\n  text: Legal Terms constitute a legally binding agreement made between you, whether personally or on behalf of\n    an entity\nrestricted_uses:\n- summary: No automated access\n  text: You will not access the Services through automated or non-human means, whether through a bot, script, or\n    otherwise.\nverification:\n  kyc: null\n \
  \ kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: You are not a minor in the jurisdiction in which you reside.\n"
source_yaml_url: https://artifacts.apis.io/take2ai/eligibility/take2ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Take2.ai's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- Recruiting
- Artificial Intelligence
- AI Agents
- Human Resources
- Talent Acquisition
- Hiring
---
