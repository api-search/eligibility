---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old or the age of majority in your jurisdiction.
    type: individual
  minimum_age:
    text: You must be at least 18 years old or the age of majority in your jurisdiction.
    value: '18'
  restricted_uses:
  - summary: Call recording compliance
    text: You are solely responsible for ensuring that call recording complies with all applicable local, state, and international laws, including those requiring consent from all parties to a call.
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
name: CatchMyCall
provenance_date: '2026-11-09'
provider_name: CatchMyCall
provider_slug: catchmycall-ai
slug: catchmycall-ai-eligibility
source_date: '2026-11-09'
source_filename: catchmycall-ai-eligibility.yml
source_heading: Eligibility
source_page: https://catchmycall.ai/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CatchMyCall\naid: catchmycall-ai\nurl: https://catchmycall.ai/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old or the age of majority in your jurisdiction.\nrestricted_uses:\n- summary: Call recording compliance\n  text: You are solely responsible for ensuring that call recording complies with all applicable local, state, and\n    international laws, including those requiring consent from all parties to a call.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n\
  \  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old or the age of majority in your jurisdiction.\n"
source_yaml_url: https://artifacts.apis.io/catchmycall-ai/eligibility/catchmycall-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from CatchMyCall's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Call Automation
- Software-as-a-Service
- India
- Business
---
