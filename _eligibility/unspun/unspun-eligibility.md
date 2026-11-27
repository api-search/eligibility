---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: This Website is offered and available to users who are 18 years of age or older.
    type: individual
  minimum_age:
    text: This Website is offered and available to users who are 18 years of age or older.
    value: '18'
  restricted_uses:
  - summary: Sharing accounts or use for others
    text: You may not make the services on our Website available to, or use the services for the benefit of anyone other than yourself (or another company). Your account cannot be shared by multiple individuals.
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
name: Unspun
provenance_date: '2026-11-10'
provider_name: Unspun
provider_slug: unspun
slug: unspun-eligibility
source_date: '2026-11-10'
source_filename: unspun-eligibility.yml
source_heading: Eligibility
source_page: https://www.unspun.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Unspun\naid: unspun\nurl: https://www.unspun.io/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: This Website is offered and available to users who are 18 years of age or older.\nrestricted_uses:\n- summary: Sharing accounts or use for others\n  text: You may not make the services on our Website available to, or use the services for the benefit of anyone\n    other than yourself (or another company). Your account cannot be shared by multiple individuals.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text:\
  \ null\nminimum_age:\n  value: '18'\n  text: This Website is offered and available to users who are 18 years of age or older.\n"
source_yaml_url: https://artifacts.apis.io/unspun/eligibility/unspun-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Unspun's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Manufacturing
- Apparel
- Fashion
- Sustainability
- Robotics
- Hardware
---
