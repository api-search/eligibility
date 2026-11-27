---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You may not use the Service and you may not accept this Agreement if you are not of a legal age to form a binding contract with Kixie.
    type: individual
  - text: if you are acting on behalf of a company or entity that you have the authority to bind such entity.
    type: business
  minimum_age:
    text: You may not use the Service and you may not accept this Agreement if you are not of a legal age to form a binding contract with Kixie.
    value: null
  restricted_uses:
  - summary: Professional use only
    text: You accept that the Services are provided for professional use only
  - summary: Calls to emergency/life-line numbers
    text: Sending any calls to life-line services, such as hospitals, fire, police, 911 or utility-related telephone numbers;
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
name: Kixie
provenance_date: '2026-11-09'
provider_name: Kixie
provider_slug: kixie
slug: kixie-eligibility
source_date: '2026-11-09'
source_filename: kixie-eligibility.yml
source_heading: Eligibility
source_page: https://www.kixie.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Kixie\naid: kixie\nurl: https://www.kixie.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You may not use the Service and you may not accept this Agreement if you are not of a legal age to form\n    a binding contract with Kixie.\n- type: business\n  text: if you are acting on behalf of a company or entity that you have the authority to bind such entity.\nrestricted_uses:\n- summary: Professional use only\n  text: You accept that the Services are provided for professional use only\n- summary: Calls to emergency/life-line\
  \ numbers\n  text: Sending any calls to life-line services, such as hospitals, fire, police, 911 or utility-related telephone\n    numbers;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: You may not use the Service and you may not accept this Agreement if you are not of a legal age to form\n    a binding contract with Kixie.\n"
source_yaml_url: https://artifacts.apis.io/kixie/eligibility/kixie-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Kixie's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Sales Engagement
- Voice
- Telephony
- SMS
- Messaging
- Contact Center
- Power Dialer
- CRM
- Webhook
- Communications
- Revenue Operations
---
