---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are doing so for an employer or client, you confirm you may agree on their behalf.
    type: business
  - text: If you are a consumer, your statutory rights are unaffected.
    type: individual
  minimum_age:
    text: You must be old enough to enter a contract where you live, and not located anywhere that would make providing this service unlawful.
    value: null
  restricted_uses:
  - summary: Unlawful or sanctioned use
    text: break the law, launder money, evade sanctions, or fund anything unlawful
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
name: focxle-com
provenance_date: '2026-11-09'
provider_name: focxle-com
provider_slug: focxle-com
slug: focxle-com-eligibility
source_date: '2026-11-09'
source_filename: focxle-com-eligibility.yml
source_heading: Eligibility
source_page: https://focxle.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: focxle-com\naid: focxle-com\nurl: https://focxle.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are doing so for an employer or client, you confirm you may agree on their behalf.\n- type: individual\n  text: If you are a consumer, your statutory rights are unaffected.\nrestricted_uses:\n- summary: Unlawful or sanctioned use\n  text: break the law, launder money, evade sanctions, or fund anything unlawful\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n\
  \  text: You must be old enough to enter a contract where you live, and not located anywhere that would make providing\n    this service unlawful.\n"
source_yaml_url: https://artifacts.apis.io/focxle-com/eligibility/focxle-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from focxle-com's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Governance
- Payments
- B2B
- Autonomous Agents
---
