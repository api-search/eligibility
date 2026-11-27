---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: offers a Collectiv Food User (either a food supplier or a buyer as the case may be)
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Non-commercial personal use only
    text: solely for Your own personal, non-commercial use
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
name: Collectiv Food
provenance_date: '2026-11-09'
provider_name: Collectiv Food
provider_slug: collectiv-food
slug: collectiv-food-eligibility
source_date: '2026-11-09'
source_filename: collectiv-food-eligibility.yml
source_heading: Eligibility
source_page: https://collectivfood.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Collectiv Food\naid: collectiv-food\nurl: https://collectivfood.com/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: offers a Collectiv Food User (either a food supplier or a buyer as the case may be)\nrestricted_uses:\n- summary: Non-commercial personal use only\n  text: solely for Your own personal, non-commercial use\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/collectiv-food/eligibility/collectiv-food-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Collectiv Food's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Applicative Saas
- Food
- Food Wholesale
- Food Distribution
- Supply Chain
- Food Tech
- Sustainability
- B2B
---
