---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are using our Services for an organization, you are agreeing to these Terms on behalf of that organization.
    type: business
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You may need to register for an account to access some or all of our Services.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: TawkitAI
provenance_date: '2026-11-10'
provider_name: TawkitAI
provider_slug: tawkitai
slug: tawkitai-eligibility
source_date: '2026-11-10'
source_filename: tawkitai-eligibility.yml
source_heading: Eligibility
source_page: https://www.copilotkit.ai/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: TawkitAI\naid: tawkitai\nurl: https://www.copilotkit.ai/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are using our Services for an organization, you are agreeing to these Terms on behalf of that organization.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You may need to register for an account to access some or all of our Services.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/tawkitai/eligibility/tawkitai-eligibility.yml
stated_fields:
- entity_types
- verification
summary_line: 2 quoted statements, read from TawkitAI's own page on 2026-11-10.
synthetic: false
tags:
- Company
- AI Agents
- Copilots
- Generative UI
- Frontend
- Developer Tools
- React
- SDK
- Open Source
- LLM
---
