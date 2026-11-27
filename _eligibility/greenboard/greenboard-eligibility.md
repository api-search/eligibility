---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export-control and sanctions restrictions
    text: used for any purposes prohibited by the Export Laws, including, but not limited to, nuclear, chemical, or biological weapons proliferation, missile systems or technology, or restricted unmanned aerial vehicle applications
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
name: Greenboard
provenance_date: '2026-11-09'
provider_name: Greenboard
provider_slug: greenboard
slug: greenboard-eligibility
source_date: '2026-11-09'
source_filename: greenboard-eligibility.yml
source_heading: Eligibility
source_page: https://www.greenboard.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Greenboard\naid: greenboard\nurl: https://www.greenboard.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Export-control and sanctions restrictions\n  text: used for any purposes prohibited by the Export Laws, including, but not limited to, nuclear, chemical, or\n    biological weapons proliferation, missile systems or technology, or restricted unmanned aerial vehicle applications\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/greenboard/eligibility/greenboard-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Greenboard's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Compliance
- RegTech
- Financial Services
- SEC
- FINRA
- Communications Archiving
- Governance
- Risk Management
- Artificial Intelligence
---
