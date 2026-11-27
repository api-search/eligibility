---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You acknowledge that you are not located in a country that is subject to a U.S. Government embargo
  entity_types:
  - text: you (either an individual or an entity)
    type: individual
  - text: you (either an individual or an entity)
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Prohibited content
    text: (f) is in any way related to any raffle, sweepstakes, contest or game requiring a fee by participants
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
name: tweekit-io
provenance_date: '2026-11-10'
provider_name: tweekit-io
provider_slug: tweekit-io
slug: tweekit-io-eligibility
source_date: '2026-11-10'
source_filename: tweekit-io-eligibility.yml
source_heading: Eligibility
source_page: https://tweekit.io/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: tweekit-io\naid: tweekit-io\nurl: https://tweekit.io/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You acknowledge that you are not located in a country that is subject to a U.S. Government embargo\nentity_types:\n- type: individual\n  text: you (either an individual or an entity)\n- type: business\n  text: you (either an individual or an entity)\nrestricted_uses:\n- summary: Prohibited content\n  text: (f) is in any way related to any raffle, sweepstakes, contest or game requiring a fee by participants\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/tweekit-io/eligibility/tweekit-io-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from tweekit-io's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- File Conversion
- Media
---
