---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old and able to form a binding contract to create and use a general PDD Cloud account.
    type: individual
  - text: If you use the Service for an organization, you represent that you have authority to accept these Terms for that organization.
    type: business
  minimum_age:
    text: You must be at least 18 years old and able to form a binding contract to create and use a general PDD Cloud account.
    value: '18'
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
name: Prompt Driven
provenance_date: '2026-11-10'
provider_name: Prompt Driven
provider_slug: prompt-driven
slug: prompt-driven-eligibility
source_date: '2026-11-10'
source_filename: prompt-driven-eligibility.yml
source_heading: Eligibility
source_page: https://promptdriven.ai/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Prompt Driven\naid: prompt-driven\nurl: https://promptdriven.ai/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old and able to form a binding contract to create and use a general PDD Cloud\n    account.\n- type: business\n  text: If you use the Service for an organization, you represent that you have authority to accept these Terms\n    for that organization.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value:\
  \ '18'\n  text: You must be at least 18 years old and able to form a binding contract to create and use a general PDD Cloud\n    account.\n"
source_yaml_url: https://artifacts.apis.io/prompt-driven/eligibility/prompt-driven-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from Prompt Driven's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Developer Tools
- Artificial Intelligence
- Code Generation
- Developer Experience
- CLI
- LLM
---
