---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Phone calls go to US and Canada numbers; no general country restriction stated in visible text.
  entity_types:
  - text: You may accept these Terms only if you are at least 18 years old and have the legal capacity to enter into a binding contract in the jurisdiction where you reside.
    type: individual
  - text: If you are using the Service on behalf of an organization, you represent that you are authorized to represent and bind that organization
    type: business
  minimum_age:
    text: You may accept these Terms only if you are at least 18 years old
    value: '18'
  restricted_uses:
  - summary: Technical preview; no production or safety-critical use
    text: They are not intended for production, enterprise, regulated, safety-critical, or unattended use.
  - summary: No professional advice or diagnosis
    text: must never be used to diagnose, prevent, treat, or cure any health condition
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
name: Rabbit
provenance_date: '2026-11-10'
provider_name: Rabbit
provider_slug: rabbit
slug: rabbit-eligibility
source_date: '2026-11-10'
source_filename: rabbit-eligibility.yml
source_heading: Eligibility
source_page: https://www.rabbit.tech/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Rabbit\naid: rabbit\nurl: https://www.rabbit.tech/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: Phone calls go to US and Canada numbers; no general country restriction stated in visible text.\nentity_types:\n- type: individual\n  text: You may accept these Terms only if you are at least 18 years old and have the legal capacity to enter into\n    a binding contract in the jurisdiction where you reside.\n- type: business\n  text: If you are using the Service on behalf of an organization, you represent that you are authorized to represent\n    and bind\
  \ that organization\nrestricted_uses:\n- summary: Technical preview; no production or safety-critical use\n  text: They are not intended for production, enterprise, regulated, safety-critical, or unattended use.\n- summary: No professional advice or diagnosis\n  text: must never be used to diagnose, prevent, treat, or cure any health condition\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You may accept these Terms only if you are at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/rabbit/eligibility/rabbit-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from Rabbit's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Consumer Hardware
- AI Devices
- Large Action Model
- Voice Assistant
- Automation
---
