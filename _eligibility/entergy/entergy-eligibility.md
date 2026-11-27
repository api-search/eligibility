---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Access to the Sites may not be legal by certain persons or in certain countries. Users who access Sites from outside the United States do so at their own risk
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Lawful use only
    text: The Sites are provided only for lawful use. Any use of the Sites for any purpose contrary to applicable law is strictly prohibited.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: you may be required to register with Entergy and create an account
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Entergy
provenance_date: '2026-11-09'
provider_name: Entergy
provider_slug: entergy
slug: entergy-eligibility
source_date: '2026-11-09'
source_filename: entergy-eligibility.yml
source_heading: Eligibility
source_page: https://www.entergy.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Entergy\naid: entergy\nurl: https://www.entergy.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Access to the Sites may not be legal by certain persons or in certain countries. Users who access Sites\n    from outside the United States do so at their own risk\nentity_types: []\nrestricted_uses:\n- summary: Lawful use only\n  text: The Sites are provided only for lawful use. Any use of the Sites for any purpose contrary to applicable\n    law is strictly prohibited.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: you may be required to register\
  \ with Entergy and create an account\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/entergy/eligibility/entergy-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
summary_line: 3 quoted statements, read from Entergy's own page on 2026-11-09.
synthetic: false
tags:
- Electricity
- Energy
- Fortune 500
- Utility
- Nuclear
- Power Generation
- Louisiana
- Geospatial
---
