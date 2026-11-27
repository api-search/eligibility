---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The products displayed on the Sites are only distributed in certain select countries.
  entity_types:
  - text: If you are a business customer, these Terms of Use will govern your purchase of products from our business-facing Sites.
    type: business
  minimum_age:
    text: You further represent and warrant that (i) you are at least 18 years of age (or the applicable age of majority in your jurisdiction)
    value: '18'
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
name: Revlon
provenance_date: '2026-11-10'
provider_name: Revlon
provider_slug: revlon
slug: revlon-eligibility
source_date: '2026-11-10'
source_filename: revlon-eligibility.yml
source_heading: Eligibility
source_page: https://www.revlon.com/pages/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Revlon\naid: revlon\nurl: https://www.revlon.com/pages/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The products displayed on the Sites are only distributed in certain select countries.\nentity_types:\n- type: business\n  text: If you are a business customer, these Terms of Use will govern your purchase of products from our business-facing\n    Sites.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You further represent and warrant that (i) you are at least 18 years of age\
  \ (or the applicable age of majority\n    in your jurisdiction)\n"
source_yaml_url: https://artifacts.apis.io/revlon/eligibility/revlon-eligibility.yml
stated_fields:
- countries
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from Revlon's own page on 2026-11-10.
synthetic: false
tags:
- Antiperspirant
- Beauty
- Beauty Tools
- Chapter 11
- Color Cosmetics
- Consumer Beauty
- Cosmetics
- Deodorant
- EDI
- Elizabeth Arden
- Fragrance
- Hair Care
- Hair Color
- Licensed Brands
- Mass Market
- Nail Care
- Personal Care
- Post Bankruptcy
- Prestige
- Private Company
- Shopify
- Skincare
- Supplier Portal
---
