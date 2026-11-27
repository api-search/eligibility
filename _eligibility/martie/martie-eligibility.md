---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: We reserve the right, but are not obligated, to limit the sales of our products or Services to any person, geographic region, or jurisdiction.
  entity_types:
  - text: Only individual people are eligible to participate in Martie's referral program.
    type: individual
  - text: Businesses may not use referral codes for affiliate lead generation.
    type: business
  minimum_age:
    text: Our Services are not targeted toward or intended for use by anyone under the age of 16.
    value: '16'
  restricted_uses:
  - summary: No commercial use or resale
    text: You must not access or use for any commercial purposes any part of the site, or any services or materials available through the site.
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
name: Martie
provenance_date: '2026-11-10'
provider_name: Martie
provider_slug: martie
slug: martie-eligibility
source_date: '2026-11-10'
source_filename: martie-eligibility.yml
source_heading: Eligibility
source_page: https://martie.com/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Martie\naid: martie\nurl: https://martie.com/policies/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: We reserve the right, but are not obligated, to limit the sales of our products or Services to any person,\n    geographic region, or jurisdiction.\nentity_types:\n- type: individual\n  text: Only individual people are eligible to participate in Martie's referral program.\n- type: business\n  text: Businesses may not use referral codes for affiliate lead generation.\nrestricted_uses:\n- summary: No commercial use or resale\n  text: You must not access or use for\
  \ any commercial purposes any part of the site, or any services or materials\n    available through the site.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: Our Services are not targeted toward or intended for use by anyone under the age of 16.\n"
source_yaml_url: https://artifacts.apis.io/martie/eligibility/martie-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Martie's own page on 2026-11-10.
synthetic: false
tags:
- Company
- E-Commerce
- Grocery
- Retail
- Marketplace
- Consumer Goods
- Food
- Overstock
- Sustainability
---
