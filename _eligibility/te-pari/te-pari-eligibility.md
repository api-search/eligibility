---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If the Buyer is acquiring Goods for the purposes of a trade or business, the Buyer acknowledges that the provisions of the Consumer Guarantees Act 1993 do not apply to the supply of Goods by the Seller to the Buyer.
    type: business
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: (b) for approved Buyer’s, by way of instalments/progress payments in accordance with the Seller’s payment schedule
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Te Pari
provenance_date: '2026-11-10'
provider_name: Te Pari
provider_slug: te-pari
slug: te-pari-eligibility
source_date: '2026-11-10'
source_filename: te-pari-eligibility.yml
source_heading: Eligibility
source_page: https://www.tepari.com/nz/pages/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Te Pari\naid: te-pari\nurl: https://www.tepari.com/nz/pages/terms-and-conditions/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If the Buyer is acquiring Goods for the purposes of a trade or business, the Buyer acknowledges that the\n    provisions of the Consumer Guarantees Act 1993 do not apply to the supply of Goods by the Seller to the Buyer.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: (b) for approved Buyer’s, by way of instalments/progress payments in accordance with the Seller’s\
  \ payment\n    schedule\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/te-pari/eligibility/te-pari-eligibility.yml
stated_fields:
- entity_types
- verification
summary_line: 2 quoted statements, read from Te Pari's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Livestock
- Equipment
- New Zealand
- Agriculture
---
