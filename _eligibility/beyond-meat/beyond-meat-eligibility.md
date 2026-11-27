---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Site is controlled and operated from facilities in the United States. Beyond Meat makes no representations that the Site is appropriate or available for use in other locations.
  entity_types:
  - text: You may use the Site only if you can form a binding contract with Beyond Meat
    type: individual
  minimum_age:
    text: Any use or access to the Site by anyone under 13 is strictly prohibited and in violation of this Agreement.
    value: '13'
  restricted_uses:
  - summary: Embargoed or blocked persons
    text: You may not use the Site if you are a resident of a country embargoed by the United States, or are a foreign person or entity blocked or denied by the United States government.
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
name: Beyond Meat
provenance_date: '2026-11-09'
provider_name: Beyond Meat
provider_slug: beyond-meat
slug: beyond-meat-eligibility
source_date: '2026-11-09'
source_filename: beyond-meat-eligibility.yml
source_heading: Eligibility
source_page: https://www.beyondmeat.com/en-US/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Beyond Meat\naid: beyond-meat\nurl: https://www.beyondmeat.com/en-US/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Site is controlled and operated from facilities in the United States. Beyond Meat makes no representations\n    that the Site is appropriate or available for use in other locations.\nentity_types:\n- type: individual\n  text: You may use the Site only if you can form a binding contract with Beyond Meat\nrestricted_uses:\n- summary: Embargoed or blocked persons\n  text: You may not use the Site if you are a resident of a country embargoed by the\
  \ United States, or are a foreign\n    person or entity blocked or denied by the United States government.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: Any use or access to the Site by anyone under 13 is strictly prohibited and in violation of this Agreement.\n"
source_yaml_url: https://artifacts.apis.io/beyond-meat/eligibility/beyond-meat-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Beyond Meat's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer
- Food
- Plant-Based
- Consumer Packaged Goods
- Sustainability
- Retail
- Food and Beverage
---
