---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Your Account is for your individual, personal and non-commercial use only
    type: individual
  minimum_age:
    text: Your access and use of the Service constitutes your representation and warranty that you are of legal age to form a binding contract, and if not of legal age, that you access and use the Services with the permission of a parent or legal guardian
    value: null
  restricted_uses:
  - summary: Non-commercial personal use only
    text: Your Account is for your individual, personal and non-commercial use only, and you may not authorize others to use your Account for any purpose.
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
name: FreshPlanet
provenance_date: '2026-11-09'
provider_name: FreshPlanet
provider_slug: freshplanet
slug: freshplanet-eligibility
source_date: '2026-11-09'
source_filename: freshplanet-eligibility.yml
source_heading: Eligibility
source_page: https://www.freshplanet.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: FreshPlanet\naid: freshplanet\nurl: https://www.freshplanet.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Your Account is for your individual, personal and non-commercial use only\nrestricted_uses:\n- summary: Non-commercial personal use only\n  text: Your Account is for your individual, personal and non-commercial use only, and you may not authorize others\n    to use your Account for any purpose.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text:\
  \ Your access and use of the Service constitutes your representation and warranty that you are of legal age\n    to form a binding contract, and if not of legal age, that you access and use the Services with the permission\n    of a parent or legal guardian\n"
source_yaml_url: https://artifacts.apis.io/freshplanet/eligibility/freshplanet-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from FreshPlanet's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Mobile Games
- Gaming
- Entertainment
- Music
- Consumer App
- New York
---
