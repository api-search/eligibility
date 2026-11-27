---
api_specs:
- filename: yuno-openapi-original.json
  format: json
  label: Yuno Payments API
  slug: yuno-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/yuno/openapi/_original/yuno-openapi-original.json
claim_count: 2
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
  - summary: Unlawful or fraudulent use
    text: use the Services for any purpose that is unlawful, illegal, fraudulent, harmful, or that advocates, promotes, incites, or instructs others to engage in illegal activity
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Company shall provide and maintain current, accurate, and complete information regarding its beneficial ownership, business activities, funding sources, and regulatory status. Yuno may apply enhanced due diligence measures for PEPs, high-risk jurisdictions, or elevated-risk business models.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Yuno
provenance_date: '2026-11-10'
provider_name: Yuno
provider_slug: yuno
slug: yuno-eligibility
source_date: '2026-11-10'
source_filename: yuno-eligibility.yml
source_heading: Eligibility
source_page: https://y.uno/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Yuno\naid: yuno\nurl: https://y.uno/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful or fraudulent use\n  text: use the Services for any purpose that is unlawful, illegal, fraudulent, harmful, or that advocates, promotes,\n    incites, or instructs others to engage in illegal activity\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Company shall provide and maintain current, accurate, and complete information regarding its beneficial\n    ownership, business\
  \ activities, funding sources, and regulatory status. Yuno may apply enhanced due diligence\n    measures for PEPs, high-risk jurisdictions, or elevated-risk business models.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/yuno/eligibility/yuno-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from Yuno's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Payments
- Payment Orchestration
- Fintech
- Checkout
- Payouts
- Subscription
---
