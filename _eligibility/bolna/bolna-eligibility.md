---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You represent that you are at least 18 years of age
    type: individual
  - text: where you accept on behalf of an entity you have authority to bind that entity
    type: business
  minimum_age:
    text: You represent that you are at least 18 years of age
    value: '18'
  restricted_uses:
  - summary: Childlike voices and minors
    text: Deploy agents using childlike voices or mannerisms, or initiate interactions that sexualise, exploit, or endanger minors
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Acceptance requires an affirmative act — ticking the consent box presented at registration and completing registration.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Bolna
provenance_date: '2026-11-09'
provider_name: Bolna
provider_slug: bolna
slug: bolna-eligibility
source_date: '2026-11-09'
source_filename: bolna-eligibility.yml
source_heading: Eligibility
source_page: https://www.bolna.ai/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bolna\naid: bolna\nurl: https://www.bolna.ai/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You represent that you are at least 18 years of age\n- type: business\n  text: where you accept on behalf of an entity you have authority to bind that entity\nrestricted_uses:\n- summary: Childlike voices and minors\n  text: Deploy agents using childlike voices or mannerisms, or initiate interactions that sexualise, exploit, or\n    endanger minors\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text:\
  \ Acceptance requires an affirmative act — ticking the consent box presented at registration and completing\n    registration.\nminimum_age:\n  value: '18'\n  text: You represent that you are at least 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/bolna/eligibility/bolna-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Bolna's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Voice AI
- Conversational AI
- Voice Agents
- Telephony
- Speech
- Call Automation
- Contact Center
- MCP
---
