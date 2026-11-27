---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You represent and warrant that you are of legal age to form a binding contract (or if not, youʼve received your parentʼs or guardianʼs permission to use the Services
    type: individual
  - text: If youʼre agreeing to these Terms on behalf of an organization or entity, you represent and warrant that you are authorized to agree to these Terms on that organization or entityʼs behalf
    type: business
  minimum_age:
    text: if you are a child under 13, please do not attempt to register for the Services or send any personal information about yourself to us.
    value: '13'
  restricted_uses:
  - summary: Spam and electoral content
    text: to generate spam, content for dissemination in electoral campaigns, use the Services in a manner that violates any applicable laws
  - summary: Harmful or unlawful content
    text: Is harmful, fraudulent, deceptive, threatening, harassing, defamatory, obscene, or otherwise objectionable;
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You may be required to sign up for an account and log-in to Chatfuel through your Google/Facebook or other third party account, and select a password and username
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Chatfuel
provenance_date: '2026-11-09'
provider_name: Chatfuel
provider_slug: chatfuel
slug: chatfuel-eligibility
source_date: '2026-11-09'
source_filename: chatfuel-eligibility.yml
source_heading: Eligibility
source_page: https://chatfuel.com/files/TermsOfUse.pdf
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Chatfuel\naid: chatfuel\nurl: https://chatfuel.com/files/TermsOfUse.pdf\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You represent and warrant that you are of legal age to form a binding contract (or if not, youʼve received\n    your parentʼs or guardianʼs permission to use the Services\n- type: business\n  text: If youʼre agreeing to these Terms on behalf of an organization or entity, you represent and warrant that\n    you are authorized to agree to these Terms on that organization or entityʼs behalf\nrestricted_uses:\n\
  - summary: Spam and electoral content\n  text: to generate spam, content for dissemination in electoral campaigns, use the Services in a manner that violates\n    any applicable laws\n- summary: Harmful or unlawful content\n  text: Is harmful, fraudulent, deceptive, threatening, harassing, defamatory, obscene, or otherwise objectionable;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You may be required to sign up for an account and log-in to Chatfuel through your Google/Facebook or other\n    third party account, and select a password and username\nminimum_age:\n  value: '13'\n  text: if you are a child under 13, please do not attempt to register for the Services or send any personal information\n    about yourself to us.\n"
source_yaml_url: https://artifacts.apis.io/chatfuel/eligibility/chatfuel-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Chatfuel's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Chatbots
- Conversational AI
- Messaging
- Marketing Automation
- Customer Service
- WhatsApp
- Instagram
- Facebook Messenger
- TikTok
- No-Code
- AI Agents
---
