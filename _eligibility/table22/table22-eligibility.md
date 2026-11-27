---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 to use the Services and create an account.
    type: individual
  minimum_age:
    text: You must be at least 18 to use the Services and create an account.
    value: '18'
  restricted_uses:
  - summary: Alcohol purchase age
    text: You must be at least 21 to purchase or receive alcohol.
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
name: Table22
provenance_date: '2026-11-10'
provider_name: Table22
provider_slug: table22
slug: table22-eligibility
source_date: '2026-11-10'
source_filename: table22-eligibility.yml
source_heading: Eligibility
source_page: https://www.table22.com/legals/website-terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Table22\naid: table22\nurl: https://www.table22.com/legals/website-terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 to use the Services and create an account.\nrestricted_uses:\n- summary: Alcohol purchase age\n  text: You must be at least 21 to purchase or receive alcohol.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 to use the Services and create an account.\n"
source_yaml_url: https://artifacts.apis.io/table22/eligibility/table22-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Table22's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Subscription Commerce
- Food and Beverage
- Hospitality
- E-Commerce
- Membership
- Recurring Revenue
- Wine Clubs
- Fulfillment
---
