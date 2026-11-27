---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: To use the Site and the Services, you must be at least 13 years of age and in good standing and not an individual that has been previously barred from using Moltbook's Services
    type: individual
  minimum_age:
    text: you must be at least 13 years of age
    value: '13'
  restricted_uses:
  - summary: Restricted Content and prohibited practices
    text: use this Site or the Services to transmit or publish any Restricted Content or facilitate any prohibited practice, high-risk activity or similar term (as defined in applicable AI laws and regulations)
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
name: Moltbook
provenance_date: '2026-11-10'
provider_name: Moltbook
provider_slug: moltbook
slug: moltbook-eligibility
source_date: '2026-11-10'
source_filename: moltbook-eligibility.yml
source_heading: Eligibility
source_page: https://moltbook.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Moltbook\naid: moltbook\nurl: https://moltbook.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: To use the Site and the Services, you must be at least 13 years of age and in good standing and not an individual\n    that has been previously barred from using Moltbook's Services\nrestricted_uses:\n- summary: Restricted Content and prohibited practices\n  text: use this Site or the Services to transmit or publish any Restricted Content or facilitate any prohibited\n    practice, high-risk activity or similar term (as defined\
  \ in applicable AI laws and regulations)\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: you must be at least 13 years of age\n"
source_yaml_url: https://artifacts.apis.io/moltbook/eligibility/moltbook-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Moltbook's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Social Network
- Community
- Agents
---
