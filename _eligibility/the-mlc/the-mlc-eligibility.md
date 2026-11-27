---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: If you access the Website, including The MLC Portal or the DURP, from outside the United States, you do so on your own initiative and are responsible for compliance with applicable laws.
  entity_types:
  - text: The Website is not intended for individuals under the age of thirteen
    type: individual
  minimum_age:
    text: The Website is not intended for individuals under the age of thirteen, and such individuals are expressly prohibited from engaging in any aspect of the Website.
    value: '13'
  restricted_uses:
  - summary: Improper business use
    text: You agree not to use the Website for improper business or undue economic advantage or gain
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
name: The MLC
provenance_date: '2026-11-10'
provider_name: The MLC
provider_slug: the-mlc
slug: the-mlc-eligibility
source_date: '2026-11-10'
source_filename: the-mlc-eligibility.yml
source_heading: Eligibility
source_page: https://www.themlc.com/terms-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: The MLC\naid: the-mlc\nurl: https://www.themlc.com/terms-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: If you access the Website, including The MLC Portal or the DURP, from outside the United States, you do\n    so on your own initiative and are responsible for compliance with applicable laws.\nentity_types:\n- type: individual\n  text: The Website is not intended for individuals under the age of thirteen\nrestricted_uses:\n- summary: Improper business use\n  text: You agree not to use the Website for improper business or undue economic advantage or gain\nverification:\n  kyc:\
  \ null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: The Website is not intended for individuals under the age of thirteen, and such individuals are expressly\n    prohibited from engaging in any aspect of the Website.\n"
source_yaml_url: https://artifacts.apis.io/the-mlc/eligibility/the-mlc-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from The MLC's own page on 2026-11-10.
synthetic: false
tags:
- Music
- Licensing
- Royalties
- Collective
---
