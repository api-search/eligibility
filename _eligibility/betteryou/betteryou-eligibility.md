---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - GB
    text: BetterYou orders can only be shipped to UK addresses; however, our products are available internationally through selected distributors.
  entity_types:
  - text: Only adults (that is, those aged 18 and over) are entitled to enter into legally binding contracts and as a result, are the only people entitled to transact through this site.
    type: individual
  minimum_age:
    text: Only adults (that is, those aged 18 and over) are entitled to enter into legally binding contracts
    value: '18'
  restricted_uses:
  - summary: No resale of products
    text: you may not sell or re-sell any of the products to anyone, including making them available for sale on any third party website
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
name: BetterYou
provenance_date: '2026-11-09'
provider_name: BetterYou
provider_slug: betteryou
slug: betteryou-eligibility
source_date: '2026-11-09'
source_filename: betteryou-eligibility.yml
source_heading: Eligibility
source_page: https://betteryou.com/pages/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BetterYou\naid: betteryou\nurl: https://betteryou.com/pages/terms-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - GB\n  excluded: []\n  text: BetterYou orders can only be shipped to UK addresses; however, our products are available internationally\n    through selected distributors.\nentity_types:\n- type: individual\n  text: Only adults (that is, those aged 18 and over) are entitled to enter into legally binding contracts and as\n    a result, are the only people entitled to transact through this site.\nrestricted_uses:\n- summary: No resale of products\n  text: you may not sell or re-sell\
  \ any of the products to anyone, including making them available for sale on any\n    third party website\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Only adults (that is, those aged 18 and over) are entitled to enter into legally binding contracts\n"
source_yaml_url: https://artifacts.apis.io/betteryou/eligibility/betteryou-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from BetterYou's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Nutrition
- Supplements
- Health
- Wellness
---
