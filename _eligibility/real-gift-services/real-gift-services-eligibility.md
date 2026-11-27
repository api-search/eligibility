---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: you represent and warrant that you are at least 18
    type: individual
  minimum_age:
    text: The Service is intended for users 18 years of age or older.
    value: '18'
  restricted_uses:
  - summary: Personal, lawful use only
    text: You agree to use the Service only for lawful, personal purposes permitted by these Terms.
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: We may, at any time and at our sole discretion, require you to verify your identity, your payment method, your address, or other registration information.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Real Gift Services
provenance_date: '2026-11-10'
provider_name: Real Gift Services
provider_slug: real-gift-services
slug: real-gift-services-eligibility
source_date: '2026-11-10'
source_filename: real-gift-services-eligibility.yml
source_heading: Eligibility
source_page: https://www.getrealgifts.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Real Gift Services\naid: real-gift-services\nurl: https://www.getrealgifts.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: you represent and warrant that you are at least 18\nrestricted_uses:\n- summary: Personal, lawful use only\n  text: You agree to use the Service only for lawful, personal purposes permitted by these Terms.\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: We may, at any time and at our sole discretion, require you to verify your identity, your payment method,\n\
  \    your address, or other registration information.\nminimum_age:\n  value: '18'\n  text: The Service is intended for users 18 years of age or older.\n"
source_yaml_url: https://artifacts.apis.io/real-gift-services/eligibility/real-gift-services-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Real Gift Services's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Gifting
- Gift Cards
- Rewards
- Loyalty
- E-Commerce
- Commerce
- Embedded Commerce
- SDK
- Webhook
---
