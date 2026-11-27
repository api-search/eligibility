---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: To access and/or use the "Services and Contents" of the KEYNUA Platform, you must have the legal capacity to contract; that is, be of legal age (18 years old) and have no legal limitations to enter into contracts.
    type: individual
  minimum_age:
    text: be of legal age (18 years old)
    value: '18'
  restricted_uses:
  - summary: Fraudulent or criminal operations
    text: Reject any Identity Registration or Request in case of the possibility or detection of fraudulent or criminal operations using said identity.
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
name: Keynua
provenance_date: '2026-11-09'
provider_name: Keynua
provider_slug: keynua
slug: keynua-eligibility
source_date: '2026-11-09'
source_filename: keynua-eligibility.yml
source_heading: Eligibility
source_page: https://www.keynua.com/en/legal/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Keynua\naid: keynua\nurl: https://www.keynua.com/en/legal/terms-and-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: To access and/or use the \"Services and Contents\" of the KEYNUA Platform, you must have the legal capacity\n    to contract; that is, be of legal age (18 years old) and have no legal limitations to enter into contracts.\nrestricted_uses:\n- summary: Fraudulent or criminal operations\n  text: Reject any Identity Registration or Request in case of the possibility or detection of fraudulent or criminal\n   \
  \ operations using said identity.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: be of legal age (18 years old)\n"
source_yaml_url: https://artifacts.apis.io/keynua/eligibility/keynua-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Keynua's own page on 2026-11-09.
synthetic: false
tags:
- Company
- E-Signature
- Digital Signature
- Identity Verification
- Biometrics
- KYC
- Onboarding
- OTP
- Webhook
- Latin America
---
