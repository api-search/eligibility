---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be legally able to enter into this agreement.
    type: individual
  - text: If you act for a business or another organization, you must have authority to bind it, and references to you include that organization.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Lawful use only
    text: Use ZRouter only for lawful purposes and within the permissions of your account and connected providers.
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
name: zrouter-si
provenance_date: '2026-11-10'
provider_name: zrouter-si
provider_slug: zrouter-si
slug: zrouter-si-eligibility
source_date: '2026-11-10'
source_filename: zrouter-si-eligibility.yml
source_heading: Eligibility
source_page: https://zrouter.si/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: zrouter-si\naid: zrouter-si\nurl: https://zrouter.si/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be legally able to enter into this agreement.\n- type: business\n  text: If you act for a business or another organization, you must have authority to bind it, and references to\n    you include that organization.\nrestricted_uses:\n- summary: Lawful use only\n  text: Use ZRouter only for lawful purposes and within the permissions of your account and connected providers.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/zrouter-si/eligibility/zrouter-si-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from zrouter-si's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- API Gateway
- OpenAI-Compatible
- Multi-Model
---
