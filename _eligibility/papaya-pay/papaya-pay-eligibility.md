---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: In order to access or use the Service, you must be a resident of the United States and at least 18 years of age or the age of majority in your state of residence, except for One Bill Pay which has a minimum requirement of 13 years of age.
  entity_types:
  - text: you must be a resident of the United States and at least 18 years of age or the age of majority in your state of residence
    type: individual
  minimum_age:
    text: at least 18 years of age or the age of majority in your state of residence, except for One Bill Pay which has a minimum requirement of 13 years of age.
    value: '18'
  restricted_uses:
  - summary: No international or P2P payments
    text: Papaya does not support international payments or peer to peer (P2P) payments.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: When you create an Account and from time to time thereafter, your Account may be subject to verification, including validation of any information you provide to us against third-party databases.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Papaya Pay
provenance_date: '2026-11-10'
provider_name: Papaya Pay
provider_slug: papaya-pay
slug: papaya-pay-eligibility
source_date: '2026-11-10'
source_filename: papaya-pay-eligibility.yml
source_heading: Eligibility
source_page: https://papayapay.com/compliance/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Papaya Pay\naid: papaya-pay\nurl: https://papayapay.com/compliance/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: In order to access or use the Service, you must be a resident of the United States and at least 18 years\n    of age or the age of majority in your state of residence, except for One Bill Pay which has a minimum requirement\n    of 13 years of age.\nentity_types:\n- type: individual\n  text: you must be a resident of the United States and at least 18 years of age or the age of majority in your\n    state of residence\nrestricted_uses:\n- summary: No international\
  \ or P2P payments\n  text: Papaya does not support international payments or peer to peer (P2P) payments.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: When you create an Account and from time to time thereafter, your Account may be subject to verification,\n    including validation of any information you provide to us against third-party databases.\nminimum_age:\n  value: '18'\n  text: at least 18 years of age or the age of majority in your state of residence, except for One Bill Pay which\n    has a minimum requirement of 13 years of age.\n"
source_yaml_url: https://artifacts.apis.io/papaya-pay/eligibility/papaya-pay-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Papaya Pay's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fintech
- Payments
- Bill Pay
- Billing
- Digital Payments
- Consumer Finance
---
