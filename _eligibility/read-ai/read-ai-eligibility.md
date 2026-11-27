---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years of age to use our Services.
    type: individual
  - text: If you use our Services on behalf of another person or entity, (a) all references to "you" throughout these Terms will include that person or entity
    type: business
  minimum_age:
    text: You must be at least 18 years of age to use our Services.
    value: '18'
  restricted_uses:
  - summary: No commercial resale
    text: Sell, resell, or commercially use our Services;
  - summary: Agentic actions require user enablement
    text: Agentic Features must be affirmatively enabled by you before Read AI's artificial intelligence may take any action on your behalf.
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
name: Read AI
provenance_date: '2026-11-10'
provider_name: Read AI
provider_slug: read-ai
slug: read-ai-eligibility
source_date: '2026-11-10'
source_filename: read-ai-eligibility.yml
source_heading: Eligibility
source_page: https://www.read.ai/termsofservice
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Read AI\naid: read-ai\nurl: https://www.read.ai/termsofservice\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years of age to use our Services.\n- type: business\n  text: If you use our Services on behalf of another person or entity, (a) all references to \"you\" throughout these\n    Terms will include that person or entity\nrestricted_uses:\n- summary: No commercial resale\n  text: Sell, resell, or commercially use our Services;\n- summary: Agentic actions require user enablement\n  text:\
  \ Agentic Features must be affirmatively enabled by you before Read AI's artificial intelligence may take\n    any action on your behalf.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years of age to use our Services.\n"
source_yaml_url: https://artifacts.apis.io/read-ai/eligibility/read-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Read AI's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Meeting Intelligence
- Artificial Intelligence
- Transcription
- Productivity
- Collaboration
- MCP
- Agents
- Webhook
- Software-as-a-Service
---
