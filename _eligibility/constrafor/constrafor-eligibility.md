---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: any use modification, reproduction, release, performance, display, or disclosure of such commercial software or commercial software documentation by the U.S. Government will be governed solely by the terms of this Agreement
    type: government
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export restrictions
    text: Customer may not remove or export from the United States or allow the export or re-export of the Services, Software or anything related thereto
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
name: Constrafor
provenance_date: '2026-11-09'
provider_name: Constrafor
provider_slug: constrafor
slug: constrafor-eligibility
source_date: '2026-11-09'
source_filename: constrafor-eligibility.yml
source_heading: Eligibility
source_page: https://www.constrafor.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Constrafor\naid: constrafor\nurl: https://www.constrafor.com/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: government\n  text: any use modification, reproduction, release, performance, display, or disclosure of such commercial software\n    or commercial software documentation by the U.S. Government will be governed solely by the terms of this Agreement\nrestricted_uses:\n- summary: Export restrictions\n  text: Customer may not remove or export from the United States or allow the export or re-export of the Services,\n    Software\
  \ or anything related thereto\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/constrafor/eligibility/constrafor-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Constrafor's own page on 2026-11-09.
synthetic: false
tags:
- Construction
- Fintech
- Software-as-a-Service
- Payments
- Risk Management
- Company
---
