---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Paid capabilities are offered exclusively to entrepreneurs, companies and other organizations acting for commercial or independent professional purposes, including automated agents acting for them.
    type: business
  - text: They are not offered for private consumer purposes. This restriction does not remove rights that mandatory law grants to a customer who is legally a consumer.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No investment, legal, tax or accounting advice
    text: Nothing on 402rates.com or in a response is investment, legal, tax or accounting advice, an offer, a solicitation, or a recommendation to buy, sell, hold, subscribe for or redeem any security, fund share or digital asset.
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
name: 402rates-com
provenance_date: '2026-11-09'
provider_name: 402rates-com
provider_slug: 402rates-com
slug: 402rates-com-eligibility
source_date: '2026-11-09'
source_filename: 402rates-com-eligibility.yml
source_heading: Eligibility
source_page: https://402rates.com/data-terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: 402rates-com\naid: 402rates-com\nurl: https://402rates.com/data-terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Paid capabilities are offered exclusively to entrepreneurs, companies and other organizations acting for\n    commercial or independent professional purposes, including automated agents acting for them.\n- type: individual\n  text: They are not offered for private consumer purposes. This restriction does not remove rights that mandatory\n    law grants to a customer who is legally a consumer.\nrestricted_uses:\n- summary:\
  \ No investment, legal, tax or accounting advice\n  text: Nothing on 402rates.com or in a response is investment, legal, tax or accounting advice, an offer, a solicitation,\n    or a recommendation to buy, sell, hold, subscribe for or redeem any security, fund share or digital asset.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/402rates-com/eligibility/402rates-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from 402rates-com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Finance
- Data
- Blockchain
- Treasury
- USDC
---
