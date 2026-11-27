---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You affirm that you are not named on, owned by, or acting on behalf of any U.S. government denied-party list
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export restrictions
    text: used for any purposes prohibited by the Export Laws, including, but not limited to, nuclear, chemical, or biological weapons proliferation, missile systems or technology, or restricted unmanned aerial vehicle applications
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
name: Raindrop
provenance_date: '2026-11-10'
provider_name: Raindrop
provider_slug: raindrop
slug: raindrop-eligibility
source_date: '2026-11-10'
source_filename: raindrop-eligibility.yml
source_heading: Eligibility
source_page: https://www.raindrop.ai/docs/security/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Raindrop\naid: raindrop\nurl: https://www.raindrop.ai/docs/security/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You affirm that you are not named on, owned by, or acting on behalf of any U.S. government denied-party\n    list\nentity_types: []\nrestricted_uses:\n- summary: Export restrictions\n  text: used for any purposes prohibited by the Export Laws, including, but not limited to, nuclear, chemical, or\n    biological weapons proliferation, missile systems or technology, or restricted unmanned aerial vehicle applications\nverification:\n  kyc: null\n  kyb: null\n\
  \  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/raindrop/eligibility/raindrop-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from Raindrop's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Agents
- Observability
- Monitoring
- LLMOps
- Developer Tools
- Tracing
---
