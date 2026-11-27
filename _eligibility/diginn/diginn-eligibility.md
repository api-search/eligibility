---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Services are directed to people residing in the United States, excluding California. The Services are not available to residents of California.
  entity_types:
  - text: By using any Service, you represent and warrant that you are 18 years of age or older, reside in one of those locations, and are fully competent to agree to and comply with these Terms.
    type: individual
  minimum_age:
    text: The Services are offered and available only to users who are 13 years of age or older
    value: '13'
  restricted_uses:
  - summary: commercial resale of food
    text: You are not permitted to resell or otherwise use food or beverages purchased through the Services for commercial purposes.
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
name: Diginn
provenance_date: '2026-11-09'
provider_name: Diginn
provider_slug: diginn
slug: diginn-eligibility
source_date: '2026-11-09'
source_filename: diginn-eligibility.yml
source_heading: Eligibility
source_page: https://www.diginn.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Diginn\naid: diginn\nurl: https://www.diginn.com/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Services are directed to people residing in the United States, excluding California. The Services are\n    not available to residents of California.\nentity_types:\n- type: individual\n  text: By using any Service, you represent and warrant that you are 18 years of age or older, reside in one of\n    those locations, and are fully competent to agree to and comply with these Terms.\nrestricted_uses:\n- summary: commercial resale of food\n  text: You are not permitted\
  \ to resell or otherwise use food or beverages purchased through the Services for commercial\n    purposes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: The Services are offered and available only to users who are 13 years of age or older\n"
source_yaml_url: https://artifacts.apis.io/diginn/eligibility/diginn-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Diginn's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Restaurant
- Food
- Delivery
- Catering
---
