---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You represent and warrant that you (and your Account Users) are not (i) located in, ordinarily resident in, or organized under the laws of any jurisdiction subject to comprehensive U.S. sanctions
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Sanctioned jurisdictions and parties
    text: You will not use, access, export, re-export, transfer, or make available the Services or any related technical data in violation of applicable export control or sanctions laws
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
name: Cin7
provenance_date: '2026-11-09'
provider_name: Cin7
provider_slug: cin7
slug: cin7-eligibility
source_date: '2026-11-09'
source_filename: cin7-eligibility.yml
source_heading: Eligibility
source_page: https://www.cin7.com/legal/terms-of-use-omni/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cin7\naid: cin7\nurl: https://www.cin7.com/legal/terms-of-use-omni/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You represent and warrant that you (and your Account Users) are not (i) located in, ordinarily resident\n    in, or organized under the laws of any jurisdiction subject to comprehensive U.S. sanctions\nentity_types: []\nrestricted_uses:\n- summary: Sanctioned jurisdictions and parties\n  text: You will not use, access, export, re-export, transfer, or make available the Services or any related technical\n    data in violation of applicable export control or sanctions\
  \ laws\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/cin7/eligibility/cin7-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from Cin7's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Inventory
- ERP
- Retail
- Integration
---
