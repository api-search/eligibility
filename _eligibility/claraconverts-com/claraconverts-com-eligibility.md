---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: By subscribing to the Service you confirm that (a) you are at least 18 years old, (b) you have the legal capacity to enter into these Terms
    type: individual
  - text: The Service is intended for B2B use; consumer subscriptions are accepted
    type: business
  minimum_age:
    text: you are at least 18 years old
    value: '18'
  restricted_uses:
  - summary: Impersonating a named human
    text: Clara is an AI; you must not configure her to claim to be a specific named human.
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
name: ClaraConverts
provenance_date: '2026-11-09'
provider_name: ClaraConverts
provider_slug: claraconverts-com
slug: claraconverts-com-eligibility
source_date: '2026-11-09'
source_filename: claraconverts-com-eligibility.yml
source_heading: Eligibility
source_page: https://claraconverts.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ClaraConverts\naid: claraconverts-com\nurl: https://claraconverts.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: By subscribing to the Service you confirm that (a) you are at least 18 years old, (b) you have the legal\n    capacity to enter into these Terms\n- type: business\n  text: The Service is intended for B2B use; consumer subscriptions are accepted\nrestricted_uses:\n- summary: Impersonating a named human\n  text: Clara is an AI; you must not configure her to claim to be a specific named human.\nverification:\n  kyc:\
  \ null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you are at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/claraconverts-com/eligibility/claraconverts-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from ClaraConverts's own page on 2026-11-09.
synthetic: false
tags:
- AI Chatbot
- Lead Capture
- Appointment Booking
- Ecommerce Checkout
- CRM Integration
- Web agency tools
---
