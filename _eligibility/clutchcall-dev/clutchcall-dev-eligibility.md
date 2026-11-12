---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old and have legal capacity to enter into a binding agreement.
    type: individual
  - text: If you accept on behalf of an organisation, you warrant that you are authorised to do so.
    type: business
  minimum_age:
    text: You must be at least 18 years old and have legal capacity to enter into a binding agreement.
    value: '18'
  restricted_uses:
  - summary: Automated decisions in employment, credit, healthcare or legal matters
    text: You must not use AI agents to make automated decisions about employment, credit, healthcare, or legal matters without a human reviewer.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Features available to you depend on your plan, your verification status, and applicable regulations in the jurisdictions you originate and terminate calls in.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: ClutchCall
provenance_date: '2026-11-09'
provider_name: ClutchCall
provider_slug: clutchcall-dev
slug: clutchcall-dev-eligibility
source_date: '2026-11-09'
source_filename: clutchcall-dev-eligibility.yml
source_heading: Eligibility
source_page: https://clutchcall.dev/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ClutchCall\naid: clutchcall-dev\nurl: https://clutchcall.dev/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old and have legal capacity to enter into a binding agreement.\n- type: business\n  text: If you accept on behalf of an organisation, you warrant that you are authorised to do so.\nrestricted_uses:\n- summary: Automated decisions in employment, credit, healthcare or legal matters\n  text: You must not use AI agents to make automated decisions about employment, credit, healthcare, or\
  \ legal matters\n    without a human reviewer.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Features available to you depend on your plan, your verification status, and applicable regulations in the\n    jurisdictions you originate and terminate calls in.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and have legal capacity to enter into a binding agreement.\n"
source_yaml_url: https://artifacts.apis.io/clutchcall-dev/eligibility/clutchcall-dev-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from ClutchCall's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Voice AI
- Real-Time Communications
- QUIC
- Telephony
- SIP
- Live Streaming
- Robotics
- AI Inference
- WebTransport
---
