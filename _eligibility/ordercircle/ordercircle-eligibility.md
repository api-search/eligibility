---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You must be at least 13 years old to use OrderCircle’s Web site(s) and service(s).
    value: '13'
  restricted_uses:
  - summary: Harassment
    text: You may not use the site to harass other users or businesses.
  - summary: Malicious code
    text: You must not abuse the site by knowingly posting malicious code, or links to malicious sites, that could harm other users.
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
name: OrderCircle
provenance_date: '2026-11-10'
provider_name: OrderCircle
provider_slug: ordercircle
slug: ordercircle-eligibility
source_date: '2026-11-10'
source_filename: ordercircle-eligibility.yml
source_heading: Eligibility
source_page: https://ordercircle.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: OrderCircle\naid: ordercircle\nurl: https://ordercircle.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Harassment\n  text: You may not use the site to harass other users or businesses.\n- summary: Malicious code\n  text: You must not abuse the site by knowingly posting malicious code, or links to malicious sites, that could\n    harm other users.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You must be at least 13 years old to use OrderCircle’s\
  \ Web site(s) and service(s).\n"
source_yaml_url: https://artifacts.apis.io/ordercircle/eligibility/ordercircle-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from OrderCircle's own page on 2026-11-10.
synthetic: false
tags:
- Company
- B2B
- Wholesale
- E-Commerce
- Order Management
- Inventory
- Invoicing
- Payments
---
