---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: refer to the individual person, company, or organization that has visited or is using the Website or Service
    type: individual
  minimum_age:
    text: A User must be at least 13 years of age.
    value: '13'
  restricted_uses:
  - summary: Export and sanctions compliance
    text: you will comply with all applicable import, re-import, export, and re-export control laws and regulations
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
name: Software
provenance_date: '2026-11-10'
provider_name: Software
provider_slug: software
slug: software-eligibility
source_date: '2026-11-10'
source_filename: software-eligibility.yml
source_heading: Eligibility
source_page: https://antenna.dev/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Software\naid: software\nurl: https://antenna.dev/legal/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: refer to the individual person, company, or organization that has visited or is using the Website or Service\nrestricted_uses:\n- summary: Export and sanctions compliance\n  text: you will comply with all applicable import, re-import, export, and re-export control laws and regulations\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: A User must be at least\
  \ 13 years of age.\n"
source_yaml_url: https://artifacts.apis.io/software/eligibility/software-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Software's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Developer Productivity
- Engineering Intelligence
- Artificial Intelligence
- Software Development
- Analytics
- Metrics
- DORA
- MCP
- Developer Experience
---
