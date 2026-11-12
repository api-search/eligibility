---
claim_count: 7
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years of age to register for an account or use the CNAPS Software or Services.
    type: individual
  - text: whether personally or on behalf of an entity (“user” or “you”)
    type: business
  minimum_age:
    text: You must be at least 18 years of age to register for an account or use the CNAPS Software or Services.
    value: '18'
  restricted_uses:
  - summary: Military and weapons uses of AI models
    text: for military applications, warfare, or military research and development.
  - summary: Sanctioned parties and trade controls
    text: You confirm that you are not, and will not permit the CNAPS Software or Services to be used by, any individual or entity subject to sanctions by the U.S., EU, UK, or United Nations.
  - summary: Political surveillance and espionage
    text: You may not use them for espionage, surveillance for political purposes, or intelligence gathering in violation of applicable laws.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: the Company is unable to verify or authenticate any information you provide to us
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: CNAPS.AI
provenance_date: '2026-11-09'
provider_name: CNAPS.AI
provider_slug: cnaps-ai
slug: cnaps-ai-eligibility
source_date: '2026-11-09'
source_filename: cnaps-ai-eligibility.yml
source_heading: Eligibility
source_page: https://cnaps.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CNAPS.AI\naid: cnaps-ai\nurl: https://cnaps.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years of age to register for an account or use the CNAPS Software or Services.\n- type: business\n  text: whether personally or on behalf of an entity (“user” or “you”)\nrestricted_uses:\n- summary: Military and weapons uses of AI models\n  text: for military applications, warfare, or military research and development.\n- summary: Sanctioned parties and trade controls\n  text: You confirm that\
  \ you are not, and will not permit the CNAPS Software or Services to be used by, any individual\n    or entity subject to sanctions by the U.S., EU, UK, or United Nations.\n- summary: Political surveillance and espionage\n  text: You may not use them for espionage, surveillance for political purposes, or intelligence gathering in violation\n    of applicable laws.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: the Company is unable to verify or authenticate any information you provide to us\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years of age to register for an account or use the CNAPS Software or Services.\n"
source_yaml_url: https://artifacts.apis.io/cnaps-ai/eligibility/cnaps-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 7 quoted statements, read from CNAPS.AI's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Generative AI
- Workflow Automation
- No-Code
- Image Generation
- Video Generation
- MCP
---
