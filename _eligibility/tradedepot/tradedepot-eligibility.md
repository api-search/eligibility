---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Select Country Nigeria Global
  minimum_age:
    text: You hereby declare that You are a human being over 18 years of age and of a sound mind, or at least the age of majority in the jurisdiction where You reside and from which You use the Services.
    value: '18'
  restricted_uses:
  - summary: Unauthorized or fraudulent use
    text: You use the Cash Advance or Your TradeDepot Wholesale Wallet for unauthorized purposes or where TradeDepot detects any abuse/misuse, breach of content, fraud or attempted fraud relating to Your use of the App;
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
name: TradeDepot
provenance_date: '2026-11-10'
provider_name: TradeDepot
provider_slug: tradedepot
slug: tradedepot-eligibility
source_date: '2026-11-10'
source_filename: tradedepot-eligibility.yml
source_heading: Eligibility
source_page: https://www.tradedepot.co/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: TradeDepot\naid: tradedepot\nurl: https://www.tradedepot.co/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Select Country Nigeria Global\nentity_types: []\nrestricted_uses:\n- summary: Unauthorized or fraudulent use\n  text: You use the Cash Advance or Your TradeDepot Wholesale Wallet for unauthorized purposes or where TradeDepot\n    detects any abuse/misuse, breach of content, fraud or attempted fraud relating to Your use of the App;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You hereby declare\
  \ that You are a human being over 18 years of age and of a sound mind, or at least the\n    age of majority in the jurisdiction where You reside and from which You use the Services.\n"
source_yaml_url: https://artifacts.apis.io/tradedepot/eligibility/tradedepot-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from TradeDepot's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Applicative Saas
- B2B Commerce
- Retail Distribution
- Consumer Packaged Goods
- E-Commerce
- Mobile SDKs
- Africa
- Nigeria
---
