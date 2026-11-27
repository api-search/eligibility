---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Site is intended for use by individuals 18 years of age and older.
    type: individual
  minimum_age:
    text: The Site is intended for use by individuals 18 years of age and older.
    value: '18'
  restricted_uses:
  - summary: Use of Technology restricted
    text: 'You will not, and will not permit any third party to: (1) access or attempt to access the Technology except as expressly provided in this Agreement'
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
name: Eudia
provenance_date: '2026-11-09'
provider_name: Eudia
provider_slug: eudia
slug: eudia-eligibility
source_date: '2026-11-09'
source_filename: eudia-eligibility.yml
source_heading: Eligibility
source_page: https://www.eudia.com/legal/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Eudia\naid: eudia\nurl: https://www.eudia.com/legal/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Site is intended for use by individuals 18 years of age and older.\nrestricted_uses:\n- summary: Use of Technology restricted\n  text: 'You will not, and will not permit any third party to: (1) access or attempt to access the Technology except\n    as expressly provided in this Agreement'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Site is\
  \ intended for use by individuals 18 years of age and older.\n"
source_yaml_url: https://artifacts.apis.io/eudia/eligibility/eudia-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Eudia's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Legal
- Legal Tech
- Artificial Intelligence
- Augmented Intelligence
- Compliance
- Contract Management
- Enterprise Software
---
