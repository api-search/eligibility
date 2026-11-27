---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: “Registered User” means an account created by an individual for the sole purpose of authentication and identity verification
    type: individual
  - text: whether as a guest or a registered user ("you", "your", “merchant”, “Registered User” or "user")
    type: business
  minimum_age:
    text: you are of legal age to enter into these Terms of Service and have the authority to do so
    value: null
  restricted_uses:
  - summary: Disruptive or unlawful conduct
    text: you agree not to disrupt or damage the website, platform or Service.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: you will not be able to use the Services until a Beam Account has been created and approved through our verification process.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Beam Checkout
provenance_date: '2026-11-09'
provider_name: Beam Checkout
provider_slug: beam-checkout
slug: beam-checkout-eligibility
source_date: '2026-11-09'
source_filename: beam-checkout-eligibility.yml
source_heading: Eligibility
source_page: https://www.beamcheckout.com/tncs
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Beam Checkout\naid: beam-checkout\nurl: https://www.beamcheckout.com/tncs\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: “Registered User” means an account created by an individual for the sole purpose of authentication and identity\n    verification\n- type: business\n  text: whether as a guest or a registered user (\"you\", \"your\", “merchant”, “Registered User” or \"user\")\nrestricted_uses:\n- summary: Disruptive or unlawful conduct\n  text: you agree not to disrupt or damage the website, platform or Service.\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: true\n  text: you will not be able to use the Services until a Beam Account has been created and approved through our\n    verification process.\nminimum_age:\n  value: null\n  text: you are of legal age to enter into these Terms of Service and have the authority to do so\n"
source_yaml_url: https://artifacts.apis.io/beam-checkout/eligibility/beam-checkout-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Beam Checkout's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Financial Services
- Payments
- Checkout
- Card Payments
- Webhook
- Thailand
- Fintech
---
