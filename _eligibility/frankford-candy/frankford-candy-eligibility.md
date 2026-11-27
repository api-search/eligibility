---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Giveaway is only open to legal residents of the forty-eight (48) contiguous United States who are at least eighteen (18) years of age. Giveaway is void in Alaska and Hawaii and where prohibited by law.
  entity_types:
  - text: By agreeing to these Terms of Service, you represent that you are at least the age of majority in your state or province of residence
    type: individual
  minimum_age:
    text: who are at least eighteen (18) years of age
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
name: Frankford Candy
provenance_date: '2026-11-09'
provider_name: Frankford Candy
provider_slug: frankford-candy
slug: frankford-candy-eligibility
source_date: '2026-11-09'
source_filename: frankford-candy-eligibility.yml
source_heading: Eligibility
source_page: https://www.frankfordcandy.com/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Frankford Candy\naid: frankford-candy\nurl: https://www.frankfordcandy.com/policies/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Giveaway is only open to legal residents of the forty-eight (48) contiguous United States who are at\n    least eighteen (18) years of age. Giveaway is void in Alaska and Hawaii and where prohibited by law.\nentity_types:\n- type: individual\n  text: By agreeing to these Terms of Service, you represent that you are at least the age of majority in your state\n    or province of residence\nrestricted_uses: []\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: who are at least eighteen (18) years of age\n"
source_yaml_url: https://artifacts.apis.io/frankford-candy/eligibility/frankford-candy-eligibility.yml
stated_fields:
- countries
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from Frankford Candy's own page on 2026-11-09.
synthetic: false
tags:
- Candy
- Chocolate
- Confectionery
- Consumer Packaged Goods
- Food
- Licensed Brands
- Novelty Candy
- Philadelphia
- Plush
- Private Company
- Seasonal
---
