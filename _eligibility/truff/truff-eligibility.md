---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: We reserve the right, but are not obligated, to limit the sales of our products or Services to any person, geographic region or jurisdiction.
  entity_types:
  - text: By agreeing to these Terms of Service, you represent that you are at least the age of majority in your state or province of residence
    type: individual
  minimum_age:
    text: You may not enroll if you are under 18 years old.
    value: '18'
  restricted_uses:
  - summary: Illegal or unauthorized use
    text: You may not use our products for any illegal or unauthorized purpose
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
name: TRUFF
provenance_date: '2026-11-10'
provider_name: TRUFF
provider_slug: truff
slug: truff-eligibility
source_date: '2026-11-10'
source_filename: truff-eligibility.yml
source_heading: Eligibility
source_page: https://www.truff.com/pages/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: TRUFF\naid: truff\nurl: https://www.truff.com/pages/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: We reserve the right, but are not obligated, to limit the sales of our products or Services to any person,\n    geographic region or jurisdiction.\nentity_types:\n- type: individual\n  text: By agreeing to these Terms of Service, you represent that you are at least the age of majority in your state\n    or province of residence\nrestricted_uses:\n- summary: Illegal or unauthorized use\n  text: You may not use our products for any illegal or unauthorized purpose\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You may not enroll if you are under 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/truff/eligibility/truff-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from TRUFF's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Consumer Packaged Goods
- Food and Beverage
- Condiments
- Direct to Consumer
- Retail
- E-Commerce
- Agentic Commerce
- Universal Commerce Protocol
- Shopify
---
