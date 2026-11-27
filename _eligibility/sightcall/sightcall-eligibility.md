---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Safety-critical and emergency uses
    text: The SightCall Services are not designed for autonomous operation of safety-critical systems, emergency response
  - summary: Regulated data
    text: Customer will not submit protected health information, payment card data, biometric identifiers
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
name: SightCall
provenance_date: '2026-11-10'
provider_name: SightCall
provider_slug: sightcall
slug: sightcall-eligibility
source_date: '2026-11-10'
source_filename: sightcall-eligibility.yml
source_heading: Eligibility
source_page: https://sightcall.com/terms-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: SightCall\naid: sightcall\nurl: https://sightcall.com/terms-conditions/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Safety-critical and emergency uses\n  text: The SightCall Services are not designed for autonomous operation of safety-critical systems, emergency response\n- summary: Regulated data\n  text: Customer will not submit protected health information, payment card data, biometric identifiers\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/sightcall/eligibility/sightcall-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 2 quoted statements, read from SightCall's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Video
- WebRTC
- Remote Support
- Field Service Management
- Augmented Reality
- Computer Vision
- Customer Service
- Insurance
- Telehealth
- Communications
---
