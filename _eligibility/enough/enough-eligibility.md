---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: '1.9 Purchaser: any natural or legal person having entered, or wishing to enter, into negotiations and/or an Agreement with ENOUGH'
    type: individual
  - text: '1.9 Purchaser: any natural or legal person having entered, or wishing to enter, into negotiations and/or an Agreement with ENOUGH'
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export control and sanctions compliance
    text: The Purchaser shall comply with all national and international (re-)export control laws and regulations.
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
name: Enough
provenance_date: '2026-11-09'
provider_name: Enough
provider_slug: enough
slug: enough-eligibility
source_date: '2026-11-09'
source_filename: enough-eligibility.yml
source_heading: Eligibility
source_page: https://www.enough-food.com/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Enough\naid: enough\nurl: https://www.enough-food.com/terms-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: '1.9 Purchaser: any natural or legal person having entered, or wishing to enter, into negotiations and/or\n    an Agreement with ENOUGH'\n- type: business\n  text: '1.9 Purchaser: any natural or legal person having entered, or wishing to enter, into negotiations and/or\n    an Agreement with ENOUGH'\nrestricted_uses:\n- summary: Export control and sanctions compliance\n  text: The Purchaser shall comply with all national\
  \ and international (re-)export control laws and regulations.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/enough/eligibility/enough-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Enough's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Food Technology
- Alternative Protein
- Sustainability
- Fermentation
- Mycoprotein
- AgTech
- Ingredients
---
