---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Reside in the United States of America
  entity_types:
  - text: You represent and warrant that you are an individual of legal age to form a binding contract
    type: individual
  minimum_age:
    text: Subscribers must be at least eighteen (18) years old.
    value: '18'
  restricted_uses:
  - summary: Non-commercial personal use only
    text: You will only use the Services you obtain for your own internal, personal, non-commercial use, and not on behalf of or for the benefit of any third party
  - summary: Subscription benefits non-transferable
    text: Subscription benefits are personal to the Subscriber and may not be shared, transferred, or resold.
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
name: Sandbox VR
provenance_date: '2026-11-10'
provider_name: Sandbox VR
provider_slug: sandbox-vr
slug: sandbox-vr-eligibility
source_date: '2026-11-10'
source_filename: sandbox-vr-eligibility.yml
source_heading: Eligibility
source_page: https://sandboxvr.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Sandbox VR\naid: sandbox-vr\nurl: https://sandboxvr.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Reside in the United States of America\nentity_types:\n- type: individual\n  text: You represent and warrant that you are an individual of legal age to form a binding contract\nrestricted_uses:\n- summary: Non-commercial personal use only\n  text: You will only use the Services you obtain for your own internal, personal, non-commercial use, and not on\n    behalf of or for the benefit of any third party\n- summary: Subscription benefits non-transferable\n\
  \  text: Subscription benefits are personal to the Subscriber and may not be shared, transferred, or resold.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Subscribers must be at least eighteen (18) years old.\n"
source_yaml_url: https://artifacts.apis.io/sandbox-vr/eligibility/sandbox-vr-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Sandbox VR's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Virtual Reality
- Entertainment
- Gaming
- Location-Based Entertainment
- Experience
- Consumer
---
