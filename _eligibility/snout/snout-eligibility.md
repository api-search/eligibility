---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You represent and warrant that you are an individual at least eighteen (18) years old and of legal age to form a binding contract.
    type: individual
  - text: If you're agreeing to the Agreement on behalf of an organization or entity, you represent and warrant that you are authorized to agree to the Agreement on that organization's or entity's behalf
    type: business
  minimum_age:
    text: You represent and warrant that you are an individual at least eighteen (18) years old and of legal age to form a binding contract.
    value: '18'
  restricted_uses:
  - summary: Unlawful or prohibited uses
    text: You will only use the Services in a manner that complies with all laws that apply to you.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You may be required to sign up for an account, verify your contact information, select a password and/or username
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Snout
provenance_date: '2026-11-10'
provider_name: Snout
provider_slug: snout
slug: snout-eligibility
source_date: '2026-11-10'
source_filename: snout-eligibility.yml
source_heading: Eligibility
source_page: https://www.snout.com/platform-terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Snout\naid: snout\nurl: https://www.snout.com/platform-terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You represent and warrant that you are an individual at least eighteen (18) years old and of legal age to\n    form a binding contract.\n- type: business\n  text: If you're agreeing to the Agreement on behalf of an organization or entity, you represent and warrant that\n    you are authorized to agree to the Agreement on that organization's or entity's behalf\nrestricted_uses:\n- summary: Unlawful or prohibited uses\n  text:\
  \ You will only use the Services in a manner that complies with all laws that apply to you.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You may be required to sign up for an account, verify your contact information, select a password and/or\n    username\nminimum_age:\n  value: '18'\n  text: You represent and warrant that you are an individual at least eighteen (18) years old and of legal age to\n    form a binding contract.\n"
source_yaml_url: https://artifacts.apis.io/snout/eligibility/snout-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Snout's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Veterinary
- Pet Care
- Wellness Plans
- Subscription
- Payments
- Healthcare
---
