---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 and able to enter a contract.
    type: individual
  - text: Seats are for named people at the organisation.
    type: business
  minimum_age:
    text: You must be at least 18 and able to enter a contract.
    value: '18'
  restricted_uses:
  - summary: No unlawful use or impersonation
    text: do not impersonate anyone or use the service for anything unlawful.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: The Colaunched badge and revenue tiers are awarded automatically when evidence meets the published requirements
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: colaunched-ai
provenance_date: '2026-11-09'
provider_name: colaunched-ai
provider_slug: colaunched-ai
slug: colaunched-ai-eligibility
source_date: '2026-11-09'
source_filename: colaunched-ai-eligibility.yml
source_heading: Eligibility
source_page: https://colaunched.ai/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: colaunched-ai\naid: colaunched-ai\nurl: https://colaunched.ai/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 and able to enter a contract.\n- type: business\n  text: Seats are for named people at the organisation.\nrestricted_uses:\n- summary: No unlawful use or impersonation\n  text: do not impersonate anyone or use the service for anything unlawful.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: The Colaunched badge and revenue tiers are awarded automatically when evidence\
  \ meets the published requirements\nminimum_age:\n  value: '18'\n  text: You must be at least 18 and able to enter a contract.\n"
source_yaml_url: https://artifacts.apis.io/colaunched-ai/eligibility/colaunched-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from colaunched-ai's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Business
- Startups
- Idea-Generation
- Market Research
---
