---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: This Website is intended strictly for individuals aged 18+ and only where such access is permitted under applicable local laws.
    type: individual
  minimum_age:
    text: This Website is intended strictly for individuals aged 18+ and only where such access is permitted under applicable local laws.
    value: '18'
  restricted_uses:
  - summary: Regional availability
    text: Products and features may not be available in all regions.
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
name: ChangeNOW
provenance_date: '2026-11-09'
provider_name: ChangeNOW
provider_slug: changenow-io
slug: changenow-io-eligibility
source_date: '2026-11-09'
source_filename: changenow-io-eligibility.yml
source_heading: Eligibility
source_page: https://changenow.io/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ChangeNOW\naid: changenow-io\nurl: https://changenow.io/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: This Website is intended strictly for individuals aged 18+ and only where such access is permitted under\n    applicable local laws.\nrestricted_uses:\n- summary: Regional availability\n  text: Products and features may not be available in all regions.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: This Website is intended strictly for individuals\
  \ aged 18+ and only where such access is permitted under\n    applicable local laws.\n"
source_yaml_url: https://artifacts.apis.io/changenow-io/eligibility/changenow-io-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from ChangeNOW's own page on 2026-11-09.
synthetic: false
tags:
- Cryptocurrency
- Exchange
- Finance
- Web3
- Platform
- Company
---
