---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: '"Customer" is typically a legal entity or a workspace that has entered into a separate individual chatbot service agreement with Talk-A-Bot.'
    type: business
  - text: '"User" means all individuals who interact with our chatbots directly or indirectly on any of the available Platforms'
    type: individual
  minimum_age:
    text: By accepting these terms, you represent that they have reached the age of majority where you live or reside; otherwise your consent is only valid with the approval of your legal representative
    value: age of majority
  restricted_uses:
  - summary: Unlawful use
    text: Are not entitled to use the bot in any way prohibited by law, regulation, governmental order or decree.
  - summary: Harassment or abuse
    text: Are prohibited from using the bot to defame, abuse, harass, stalk, threaten, or otherwise violate the legal rights of others.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Users can only access our chatbots upon invitation received from our Customers approving to use the chatbot and providing certain information to identify Users are associated to Customers.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Talk-A-Bot
provenance_date: '2026-11-10'
provider_name: Talk-A-Bot
provider_slug: talk-a-bot
slug: talk-a-bot-eligibility
source_date: '2026-11-10'
source_filename: talk-a-bot-eligibility.yml
source_heading: Eligibility
source_page: https://talkabot.net/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Talk-A-Bot\naid: talk-a-bot\nurl: https://talkabot.net/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: '\"Customer\" is typically a legal entity or a workspace that has entered into a separate individual chatbot\n    service agreement with Talk-A-Bot.'\n- type: individual\n  text: '\"User\" means all individuals who interact with our chatbots directly or indirectly on any of the available\n    Platforms'\nrestricted_uses:\n- summary: Unlawful use\n  text: Are not entitled to use the bot in any way prohibited by law, regulation,\
  \ governmental order or decree.\n- summary: Harassment or abuse\n  text: Are prohibited from using the bot to defame, abuse, harass, stalk, threaten, or otherwise violate the legal\n    rights of others.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Users can only access our chatbots upon invitation received from our Customers approving to use the chatbot\n    and providing certain information to identify Users are associated to Customers.\nminimum_age:\n  value: age of majority\n  text: By accepting these terms, you represent that they have reached the age of majority where you live or reside;\n    otherwise your consent is only valid with the approval of your legal representative\n"
source_yaml_url: https://artifacts.apis.io/talk-a-bot/eligibility/talk-a-bot-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Talk-A-Bot's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Chatbots
- Conversational AI
- Enterprise Software
- Compliance
- Customer Service
- Artificial Intelligence
---
