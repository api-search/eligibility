---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: IF YOU ARE ENTERING INTO THIS AGREEMENT ON BEHALF OF A COMPANY OR OTHER LEGAL ENTITY, YOU WARRANT AND REPRESENT THAT YOU HAVE THE AUTHORITY TO BIND SUCH ENTITY
    type: business
  - text: THE INDIVIDUAL OR LEGAL ENTITY USING OR LICENSING THE SERVICES UNDER THIS AGREEMENT
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Sanctions and export control
    text: Neither Party shall permit the Services to be used in connection with any sanctioned person or territory, or in violation of any applicable export control law.
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
name: Centrik
provenance_date: '2026-11-09'
provider_name: Centrik
provider_slug: centrik
slug: centrik-eligibility
source_date: '2026-11-09'
source_filename: centrik-eligibility.yml
source_heading: Eligibility
source_page: https://www.trustflight.com/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Centrik\naid: centrik\nurl: https://www.trustflight.com/terms-and-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: IF YOU ARE ENTERING INTO THIS AGREEMENT ON BEHALF OF A COMPANY OR OTHER LEGAL ENTITY, YOU WARRANT AND REPRESENT\n    THAT YOU HAVE THE AUTHORITY TO BIND SUCH ENTITY\n- type: individual\n  text: THE INDIVIDUAL OR LEGAL ENTITY USING OR LICENSING THE SERVICES UNDER THIS AGREEMENT\nrestricted_uses:\n- summary: Sanctions and export control\n  text: Neither Party shall permit the Services to be used\
  \ in connection with any sanctioned person or territory,\n    or in violation of any applicable export control law.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/centrik/eligibility/centrik-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Centrik's own page on 2026-11-09.
synthetic: false
tags:
- Quality Management
- Safety Management
- Risk Management
- Compliance
- Aerospace
- MRO
- Regulators
---
