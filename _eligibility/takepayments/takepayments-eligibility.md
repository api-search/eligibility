---
claim_count: 1
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
  - summary: Breaches of law or fraud
    text: You must not use the Site in any way that breaches any applicable laws or regulations or in any way that has any unlawful or fraudulent purpose or effect.
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
name: takepayments
provenance_date: '2026-11-10'
provider_name: takepayments
provider_slug: takepayments
slug: takepayments-eligibility
source_date: '2026-11-10'
source_filename: takepayments-eligibility.yml
source_heading: Eligibility
source_page: https://www.takepayments.com/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: takepayments\naid: takepayments\nurl: https://www.takepayments.com/terms-and-conditions/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Breaches of law or fraud\n  text: You must not use the Site in any way that breaches any applicable laws or regulations or in any way that\n    has any unlawful or fraudulent purpose or effect.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/takepayments/eligibility/takepayments-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from takepayments's own page on 2026-11-10.
synthetic: false
tags:
- Payments
- United Kingdom
- Payment Gateway
- Payment Processing
- Card Payments
- Card Machines
- In-Person Payments
- E-Commerce
- PSP
- Acquiring
---
