---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    - CA
    text: We provide our Services use only by persons located in the United States and Canada.
  entity_types:
  - text: Only those who are 18 years of age or older and who reside in the United States or Canada. are allowed to use or access our Services or to create an account.
    type: individual
  minimum_age:
    text: Only those who are 18 years of age or older and who reside in the United States or Canada.
    value: '18'
  restricted_uses:
  - summary: Personal use only
    text: that our Services are for your personal use only and that you will not use our Services for commercial purposes;
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You need an account on our App to access our Services.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Flashfood
provenance_date: '2026-11-09'
provider_name: Flashfood
provider_slug: flashfood
slug: flashfood-eligibility
source_date: '2026-11-09'
source_filename: flashfood-eligibility.yml
source_heading: Eligibility
source_page: https://flashfood.com/en/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Flashfood\naid: flashfood\nurl: https://flashfood.com/en/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  - CA\n  excluded: []\n  text: We provide our Services use only by persons located in the United States and Canada.\nentity_types:\n- type: individual\n  text: Only those who are 18 years of age or older and who reside in the United States or Canada. are allowed to\n    use or access our Services or to create an account.\nrestricted_uses:\n- summary: Personal use only\n  text: that our Services are for your personal use only and that you will not use our Services for commercial purposes;\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You need an account on our App to access our Services.\nminimum_age:\n  value: '18'\n  text: Only those who are 18 years of age or older and who reside in the United States or Canada.\n"
source_yaml_url: https://artifacts.apis.io/flashfood/eligibility/flashfood-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Flashfood's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Food Waste
- Grocery
- Retail
- Sustainability
- Marketplace
- Consumer App
- Food Tech
---
