---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: In order to use SimpliRoute, you must be at least 18 years of age and have full legal capacity.
    type: individual
  - text: If you access SimpliRoute on behalf of a company or entity, you personally represent that you have the requisite authority and agency to bind such company or entity to these Terms.
    type: business
  minimum_age:
    text: you must be at least 18 years of age and have full legal capacity
    value: '18'
  restricted_uses:
  - summary: No competing products or research
    text: Not use SimpliRoute for research or creating competing products.
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
name: Simpliroute
provenance_date: '2026-11-10'
provider_name: Simpliroute
provider_slug: simpliroute
slug: simpliroute-eligibility
source_date: '2026-11-10'
source_filename: simpliroute-eligibility.yml
source_heading: Eligibility
source_page: https://simpliroute.com/en/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Simpliroute\naid: simpliroute\nurl: https://simpliroute.com/en/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: In order to use SimpliRoute, you must be at least 18 years of age and have full legal capacity.\n- type: business\n  text: If you access SimpliRoute on behalf of a company or entity, you personally represent that you have the requisite\n    authority and agency to bind such company or entity to these Terms.\nrestricted_uses:\n- summary: No competing products or research\n  text: Not use SimpliRoute for\
  \ research or creating competing products.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you must be at least 18 years of age and have full legal capacity\n"
source_yaml_url: https://artifacts.apis.io/simpliroute/eligibility/simpliroute-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Simpliroute's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Logistics
- Route Optimization
- Last Mile Delivery
- Delivery Management
- Fleet Management
- Transportation
- Webhook
---
