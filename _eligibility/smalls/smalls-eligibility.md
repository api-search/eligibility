---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: We reserve the right, but are not obligated, to limit the sales of our products or Services to any person, geographic region or jurisdiction.
  entity_types:
  - text: Eligibility is limited to individuals only.
    type: individual
  minimum_age:
    text: you represent that you are at least the age of majority in your state or province of residence
    value: age of majority
  restricted_uses:
  - summary: Affiliate lead generation by businesses
    text: Smalls’s Refer-a-Friend Program cannot be used by businesses for affiliate lead generation as determined in Smalls’s sole discretion.
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
name: Smalls
provenance_date: '2026-11-10'
provider_name: Smalls
provider_slug: smalls
slug: smalls-eligibility
source_date: '2026-11-10'
source_filename: smalls-eligibility.yml
source_heading: Eligibility
source_page: https://www.smalls.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Smalls\naid: smalls\nurl: https://www.smalls.com/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: We reserve the right, but are not obligated, to limit the sales of our products or Services to any person,\n    geographic region or jurisdiction.\nentity_types:\n- type: individual\n  text: Eligibility is limited to individuals only.\nrestricted_uses:\n- summary: Affiliate lead generation by businesses\n  text: Smalls’s Refer-a-Friend Program cannot be used by businesses for affiliate lead generation as determined\n    in Smalls’s sole discretion.\nverification:\n  kyc:\
  \ null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: age of majority\n  text: you represent that you are at least the age of majority in your state or province of residence\n"
source_yaml_url: https://artifacts.apis.io/smalls/eligibility/smalls-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Smalls's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Pet Care
- Pet Food
- E-Commerce
- Direct to Consumer
- Subscription
- Consumer Packaged Goods
- Food and Beverage
- Retail
---
