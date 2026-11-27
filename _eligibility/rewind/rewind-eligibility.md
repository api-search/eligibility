---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You're not located in or organized under the laws of any embargoed jurisdiction or on any government sanctions list
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No illegal or harmful use
    text: Not use our Services for anything illegal or harmful
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
name: Rewind
provenance_date: '2026-11-10'
provider_name: Rewind
provider_slug: rewind
slug: rewind-eligibility
source_date: '2026-11-10'
source_filename: rewind-eligibility.yml
source_heading: Eligibility
source_page: https://rewind.com/legal/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Rewind\naid: rewind\nurl: https://rewind.com/legal/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You're not located in or organized under the laws of any embargoed jurisdiction or on any government sanctions\n    list\nentity_types: []\nrestricted_uses:\n- summary: No illegal or harmful use\n  text: Not use our Services for anything illegal or harmful\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/rewind/eligibility/rewind-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from Rewind's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Cloud
- Backup
- Data Recovery
- Software-as-a-Service
- Data Protection
- Disaster Recovery
- Security
---
