---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: you declare that you are a natural person with full capacity to enter into this agreement.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No harm to Spare or others
    text: You may not use our services, nor your access to our website, software or systems to cause harm or attempt to cause harm to Spare or any other juristic or natural person.
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
name: Spare Payments
provenance_date: '2026-11-10'
provider_name: Spare Payments
provider_slug: spare-payments
slug: spare-payments-eligibility
source_date: '2026-11-10'
source_filename: spare-payments-eligibility.yml
source_heading: Eligibility
source_page: https://www.paywithspare.com/legal
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Spare Payments\naid: spare-payments\nurl: https://www.paywithspare.com/legal\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: you declare that you are a natural person with full capacity to enter into this agreement.\nrestricted_uses:\n- summary: No harm to Spare or others\n  text: You may not use our services, nor your access to our website, software or systems to cause harm or attempt\n    to cause harm to Spare or any other juristic or natural person.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\n\
  minimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/spare-payments/eligibility/spare-payments-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Spare Payments's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Payments
- Education
- Schools
- Cashless Payments
- EdTech
- Attendance
- Webhook
---
