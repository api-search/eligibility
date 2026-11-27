---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Datacor website is intended for adults, including representatives of Datacor’s commercial customers.
    type: individual
  minimum_age:
    text: The Datacor website is intended for adults, including representatives of Datacor’s commercial customers.
    value: null
  restricted_uses:
  - summary: Unauthorized use of website
    text: Unauthorized use of this website may give rise to a claim for damages and/or be a criminal offence.
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
name: Datacor
provenance_date: '2026-11-09'
provider_name: Datacor
provider_slug: datacor
slug: datacor-eligibility
source_date: '2026-11-09'
source_filename: datacor-eligibility.yml
source_heading: Eligibility
source_page: https://www.datacor.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Datacor\naid: datacor\nurl: https://www.datacor.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Datacor website is intended for adults, including representatives of Datacor’s commercial customers.\nrestricted_uses:\n- summary: Unauthorized use of website\n  text: Unauthorized use of this website may give rise to a claim for damages and/or be a criminal offence.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: The Datacor website is intended\
  \ for adults, including representatives of Datacor’s commercial customers.\n"
source_yaml_url: https://artifacts.apis.io/datacor/eligibility/datacor-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Datacor's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Enterprise Software
- ERP
- Process Manufacturing
- Chemical Distribution
- Chemical Process Simulation
- Formulation Management
- LIMS
- Animal Nutrition
- Manufacturing
---
