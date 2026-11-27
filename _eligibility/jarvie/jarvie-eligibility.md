---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 to use Jarvie, and you confirm you are.
    type: individual
  minimum_age:
    text: You must be at least 18 to use Jarvie, and you confirm you are.
    value: '18'
  restricted_uses:
  - summary: Commercial use
    text: Jarvie is for personal, family, or household use only — not commercial use without our written agreement.
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
name: Jarvie
provenance_date: '2026-11-09'
provider_name: Jarvie
provider_slug: jarvie
slug: jarvie-eligibility
source_date: '2026-11-09'
source_filename: jarvie-eligibility.yml
source_heading: Eligibility
source_page: https://heyjarvie.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Jarvie\naid: jarvie\nurl: https://heyjarvie.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 to use Jarvie, and you confirm you are.\nrestricted_uses:\n- summary: Commercial use\n  text: Jarvie is for personal, family, or household use only — not commercial use without our written agreement.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 to use Jarvie, and you confirm you are.\n"
source_yaml_url: https://artifacts.apis.io/jarvie/eligibility/jarvie-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Jarvie's own page on 2026-11-09.
synthetic: false
tags:
- Company
- AI Assistant
- Messaging
- iMessage
- SMS
- Group Chat
- Productivity
- Consumer
- Chatbots
---
