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
  - summary: Regulatory approval / off-label use
    text: (iii) any use of the Deliverables for which they have not been approved by a regulatory authority, including, but not limited to “off -label” use.
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
name: Capitainer
provenance_date: '2026-11-09'
provider_name: Capitainer
provider_slug: capitainer
slug: capitainer-eligibility
source_date: '2026-11-09'
source_filename: capitainer-eligibility.yml
source_heading: Eligibility
source_page: https://capitainer.com/wp-content/uploads/2025/11/TERMS-AND-CONDITIONS-US.pdf
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Capitainer\naid: capitainer\nurl: https://capitainer.com/wp-content/uploads/2025/11/TERMS-AND-CONDITIONS-US.pdf\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Regulatory approval / off-label use\n  text: (iii) any use of the Deliverables for which they have not been approved by a regulatory authority, including,\n    but not limited to “off -label” use.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/capitainer/eligibility/capitainer-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Capitainer's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Microsampling
- Biotechnology
- Laboratory
- Instruments
---
