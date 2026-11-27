---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: you have the authority to enter into this agreement on behalf of any organization or person for whom you are using the platform
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Academic non-commercial use
    text: If your plan includes an academic discount, it is designated for academic, non-commercial use.
  - summary: Black Opal non-commercial licence
    text: Black Opal is licensed as a personal, non-exclusive, non-transferable, limited license product, solely for internal, non-commercial use.
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
name: Q Ctrl
provenance_date: '2026-11-10'
provider_name: Q Ctrl
provider_slug: q-ctrl
slug: q-ctrl-eligibility
source_date: '2026-11-10'
source_filename: q-ctrl-eligibility.yml
source_heading: Eligibility
source_page: https://q-ctrl.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Q Ctrl\naid: q-ctrl\nurl: https://q-ctrl.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: you have the authority to enter into this agreement on behalf of any organization or person for whom you\n    are using the platform\nrestricted_uses:\n- summary: Academic non-commercial use\n  text: If your plan includes an academic discount, it is designated for academic, non-commercial use.\n- summary: Black Opal non-commercial licence\n  text: Black Opal is licensed as a personal, non-exclusive, non-transferable, limited license product,\
  \ solely for\n    internal, non-commercial use.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/q-ctrl/eligibility/q-ctrl-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Q Ctrl's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Quantum Computing
- Quantum Control
- Quantum Sensing
- Error Suppression
- Developer Tools
- SDK
- GraphQL API
---
