---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old (or the age of majority where you live) and able to form a binding contract.
    type: individual
  minimum_age:
    text: You must be at least 18 years old (or the age of majority where you live)
    value: '18'
  restricted_uses:
  - summary: Unlawful AI-generated content
    text: misuse AI features to generate unlawful content
  - summary: Storing data not permitted to store
    text: use the Service to store data you are not permitted to store
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Beta access may be invite-only or limited.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: BaseThread
provenance_date: '2026-11-09'
provider_name: BaseThread
provider_slug: basethread-ai
slug: basethread-ai-eligibility
source_date: '2026-11-09'
source_filename: basethread-ai-eligibility.yml
source_heading: Eligibility
source_page: https://basethread.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BaseThread\naid: basethread-ai\nurl: https://basethread.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old (or the age of majority where you live) and able to form a binding contract.\nrestricted_uses:\n- summary: Unlawful AI-generated content\n  text: misuse AI features to generate unlawful content\n- summary: Storing data not permitted to store\n  text: use the Service to store data you are not permitted to store\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Beta\
  \ access may be invite-only or limited.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old (or the age of majority where you live)\n"
source_yaml_url: https://artifacts.apis.io/basethread-ai/eligibility/basethread-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from BaseThread's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Collaboration
- Productivity
- Teamware
- Software-as-a-Service
---
