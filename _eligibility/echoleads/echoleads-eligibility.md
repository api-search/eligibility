---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old and capable of entering into a binding contract.
    type: individual
  - text: If you are using the Services on behalf of an organization, you represent that you have the authority to bind that organization to these Terms.
    type: business
  minimum_age:
    text: You must be at least 18 years old and capable of entering into a binding contract.
    value: '18'
  restricted_uses:
  - summary: Unwanted or deceptive calls
    text: Harass, abuse, or harm individuals through unwanted or deceptive calls.
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
name: EchoLeads
provenance_date: '2026-11-09'
provider_name: EchoLeads
provider_slug: echoleads
slug: echoleads-eligibility
source_date: '2026-11-09'
source_filename: echoleads-eligibility.yml
source_heading: Eligibility
source_page: https://echoleads.ai/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: EchoLeads\naid: echoleads\nurl: https://echoleads.ai/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old and capable of entering into a binding contract.\n- type: business\n  text: If you are using the Services on behalf of an organization, you represent that you have the authority to\n    bind that organization to these Terms.\nrestricted_uses:\n- summary: Unwanted or deceptive calls\n  text: Harass, abuse, or harm individuals through unwanted or deceptive calls.\nverification:\n  kyc:\
  \ null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and capable of entering into a binding contract.\n"
source_yaml_url: https://artifacts.apis.io/echoleads/eligibility/echoleads-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from EchoLeads's own page on 2026-11-09.
synthetic: false
tags:
- AI voice sales
- AI Voice Agents
- cold calling automation
- AI SDR
- Lead Generation
- Conversational AI
- omnichannel sales automation
- Appointment Scheduling
- WhatsApp Automation
- Instagram DM automation
- Voice AI
- Sales Automation
- India
---
