---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Customer may not export or allow export of the Services to Embargoed Countries; no specific countries are named.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export controls and embargoes
    text: Customer may not provide to any person or export or re-export or allow the export or re-export of the Services or any software or anything related thereto
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
name: PickTrace
provenance_date: '2026-11-10'
provider_name: PickTrace
provider_slug: picktrace
slug: picktrace-eligibility
source_date: '2026-11-10'
source_filename: picktrace-eligibility.yml
source_heading: Eligibility
source_page: https://www.picktrace.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: PickTrace\naid: picktrace\nurl: https://www.picktrace.com/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Customer may not export or allow export of the Services to Embargoed Countries; no specific countries are\n    named.\nentity_types: []\nrestricted_uses:\n- summary: Export controls and embargoes\n  text: Customer may not provide to any person or export or re-export or allow the export or re-export of the Services\n    or any software or anything related thereto\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n\
  \  text: null\n"
source_yaml_url: https://artifacts.apis.io/picktrace/eligibility/picktrace-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from PickTrace's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Agriculture
- AgTech
- Workforce Management
- Labor Tracking
- Farm Management
- Harvest Management
- Time Tracking
- Payroll
- Piecework
---
