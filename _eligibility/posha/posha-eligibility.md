---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Service is limited to the contiguous United States; we do not currently ship to or service Alaska, Hawaii, U.S. territories, or international locations.
  entity_types:
  - text: You must be 18+ to use the Services.
    type: individual
  minimum_age:
    text: You must be 18+ to use the Services.
    value: '18'
  restricted_uses:
  - summary: Commercial or industrial use
    text: (vi) commercial/industrial use
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
name: Posha
provenance_date: '2026-11-10'
provider_name: Posha
provider_slug: posha
slug: posha-eligibility
source_date: '2026-11-10'
source_filename: posha-eligibility.yml
source_heading: Eligibility
source_page: https://www.posha.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Posha\naid: posha\nurl: https://www.posha.com/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Service is limited to the contiguous United States; we do not currently ship to or service Alaska, Hawaii,\n    U.S. territories, or international locations.\nentity_types:\n- type: individual\n  text: You must be 18+ to use the Services.\nrestricted_uses:\n- summary: Commercial or industrial use\n  text: (vi) commercial/industrial use\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be 18+\
  \ to use the Services.\n"
source_yaml_url: https://artifacts.apis.io/posha/eligibility/posha-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Posha's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Consumer
- Kitchen Robotics
- Home Automation
- Cooking
- Culinary AI
- Consumer Hardware
- Robotics
- Appliances
---
