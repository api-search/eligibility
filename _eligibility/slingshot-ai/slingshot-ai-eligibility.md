---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    - CA
    - AU
    - NZ
    text: Ash is offered only to individuals physically located in the United States, Canada, Australia, or New Zealand, except where we expressly authorize otherwise in writing.
  entity_types:
  - text: Ash is offered only to individuals physically located in the United States, Canada, Australia, or New Zealand
    type: individual
  minimum_age:
    text: The Application and Services are intended only for adults aged 18 or older and are not directed to anyone under 18.
    value: '18'
  restricted_uses:
  - summary: No false emergency reports
    text: You may not report false emergencies relating to yourself, others, or vulnerable populations including children, elders, or people with disabilities;
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
name: Slingshot AI
provenance_date: '2026-11-10'
provider_name: Slingshot AI
provider_slug: slingshot-ai
slug: slingshot-ai-eligibility
source_date: '2026-11-10'
source_filename: slingshot-ai-eligibility.yml
source_heading: Eligibility
source_page: https://www.talktoash.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Slingshot AI\naid: slingshot-ai\nurl: https://www.talktoash.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  - CA\n  - AU\n  - NZ\n  excluded: []\n  text: Ash is offered only to individuals physically located in the United States, Canada, Australia, or New Zealand,\n    except where we expressly authorize otherwise in writing.\nentity_types:\n- type: individual\n  text: Ash is offered only to individuals physically located in the United States, Canada, Australia, or New Zealand\nrestricted_uses:\n- summary: No false emergency reports\n  text: You may not report false emergencies relating\
  \ to yourself, others, or vulnerable populations including children,\n    elders, or people with disabilities;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Application and Services are intended only for adults aged 18 or older and are not directed to anyone\n    under 18.\n"
source_yaml_url: https://artifacts.apis.io/slingshot-ai/eligibility/slingshot-ai-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Slingshot AI's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Mental Health
- Artificial Intelligence
- Healthcare
- Digital Therapeutics
- Chatbots
- Consumer App
---
