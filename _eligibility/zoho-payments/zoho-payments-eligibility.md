---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: We provide cloud software and applications for businesses, including associated offline and mobile applications
    type: business
  minimum_age:
    text: You must be of legal age to enter into a binding agreement in order to accept the Agreement.
    value: legal age
  restricted_uses:
  - summary: Illegal or unauthorized activity
    text: We reserve the right to terminate your access to the Services if there are reasonable grounds to believe that you have used the Services for any illegal or unauthorized activity.
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
name: Zoho Payments
provenance_date: '2026-11-10'
provider_name: Zoho Payments
provider_slug: zoho-payments
slug: zoho-payments-eligibility
source_date: '2026-11-10'
source_filename: zoho-payments-eligibility.yml
source_heading: Eligibility
source_page: https://www.zoho.com/terms.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Zoho Payments\naid: zoho-payments\nurl: https://www.zoho.com/terms.html\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: We provide cloud software and applications for businesses, including associated offline and mobile applications\nrestricted_uses:\n- summary: Illegal or unauthorized activity\n  text: We reserve the right to terminate your access to the Services if there are reasonable grounds to believe\n    that you have used the Services for any illegal or unauthorized activity.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: legal age\n  text: You must be of legal age to enter into a binding agreement in order to accept the Agreement.\n"
source_yaml_url: https://artifacts.apis.io/zoho-payments/eligibility/zoho-payments-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Zoho Payments's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Payments
- Fintech
- Online Payments
---
