---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: All capable individuals over 18 years old who complete the subscription process and express acceptance of these terms and the privacy policy can be Users.
    type: individual
  minimum_age:
    text: All capable individuals over 18 years old who complete the subscription process and express acceptance of these terms and the privacy policy can be Users.
    value: '18'
  restricted_uses:
  - summary: Medical or therapeutic use
    text: The use of Zapia AI for medical or therapeutic purposes is strictly prohibited.
  - summary: Not a substitute for health care professionals
    text: It is absolutely prohibited to Use Zapia AI as a substitute for health care professionals.
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
name: Zapia
provenance_date: '2026-11-10'
provider_name: Zapia
provider_slug: zapia
slug: zapia-eligibility
source_date: '2026-11-10'
source_filename: zapia-eligibility.yml
source_heading: Eligibility
source_page: https://zapia.com/terminos?lang=en
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Zapia\naid: zapia\nurl: https://zapia.com/terminos?lang=en\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: All capable individuals over 18 years old who complete the subscription process and express acceptance of\n    these terms and the privacy policy can be Users.\nrestricted_uses:\n- summary: Medical or therapeutic use\n  text: The use of Zapia AI for medical or therapeutic purposes is strictly prohibited.\n- summary: Not a substitute for health care professionals\n  text: It is absolutely prohibited to Use Zapia AI as a substitute\
  \ for health care professionals.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: All capable individuals over 18 years old who complete the subscription process and express acceptance of\n    these terms and the privacy policy can be Users.\n"
source_yaml_url: https://artifacts.apis.io/zapia/eligibility/zapia-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Zapia's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Assistant
- Conversational AI
- WhatsApp
- Consumer
- Latin America
- Messaging
---
