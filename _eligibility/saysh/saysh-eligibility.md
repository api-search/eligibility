---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: By agreeing to these Terms of Service, you represent that you are at least the age of majority in your state, province of residence, national country
    type: individual
  minimum_age:
    text: you represent that you are at least the age of majority in your state, province of residence, national country
    value: age of majority
  restricted_uses:
  - summary: Illegal or unauthorized purposes
    text: You may not use our products or services for any illegal or unauthorized purpose
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
name: Saysh
provenance_date: '2026-11-10'
provider_name: Saysh
provider_slug: saysh
slug: saysh-eligibility
source_date: '2026-11-10'
source_filename: saysh-eligibility.yml
source_heading: Eligibility
source_page: https://saysh.com/pages/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Saysh\naid: saysh\nurl: https://saysh.com/pages/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: By agreeing to these Terms of Service, you represent that you are at least the age of majority in your state,\n    province of residence, national country\nrestricted_uses:\n- summary: Illegal or unauthorized purposes\n  text: You may not use our products or services for any illegal or unauthorized purpose\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: age of majority\n  text:\
  \ you represent that you are at least the age of majority in your state, province of residence, national country\n"
source_yaml_url: https://artifacts.apis.io/saysh/eligibility/saysh-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Saysh's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Consumer
- Footwear
- Retail
- E-Commerce
- Apparel
- Direct to Consumer
- Shopify
---
