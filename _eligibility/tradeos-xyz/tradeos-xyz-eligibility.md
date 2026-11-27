---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You may not use the Service if you are located in, ordinarily resident in, or a person or entity subject to sanctions or other restrictions that would make your use unlawful.
  entity_types:
  - text: You must be at least 18 years old, have legal capacity to enter into these Terms
    type: individual
  - text: If you use the Service on behalf of a company or other entity, you represent that you have authority to bind that entity to these Terms.
    type: business
  minimum_age:
    text: You must be at least 18 years old
    value: '18'
  restricted_uses:
  - summary: Managing third-party assets or accounts
    text: You may not use the Service to manage assets or accounts for third parties.
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
name: tradeos-xyz
provenance_date: '2026-11-10'
provider_name: tradeos-xyz
provider_slug: tradeos-xyz
slug: tradeos-xyz-eligibility
source_date: '2026-11-10'
source_filename: tradeos-xyz-eligibility.yml
source_heading: Eligibility
source_page: https://ai.tradeos.xyz/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: tradeos-xyz\naid: tradeos-xyz\nurl: https://ai.tradeos.xyz/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You may not use the Service if you are located in, ordinarily resident in, or a person or entity subject\n    to sanctions or other restrictions that would make your use unlawful.\nentity_types:\n- type: individual\n  text: You must be at least 18 years old, have legal capacity to enter into these Terms\n- type: business\n  text: If you use the Service on behalf of a company or other entity, you represent that you have authority to\n    bind that entity to these\
  \ Terms.\nrestricted_uses:\n- summary: Managing third-party assets or accounts\n  text: You may not use the Service to manage assets or accounts for third parties.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/tradeos-xyz/eligibility/tradeos-xyz-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from tradeos-xyz's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Trading
- Fintech
- Automation
- Market Data
---
