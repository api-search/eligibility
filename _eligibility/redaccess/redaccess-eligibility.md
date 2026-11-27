---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Site is only intended for individuals aged 13 years or older.
    type: individual
  minimum_age:
    text: The Site is only intended for individuals aged 13 years or older.
    value: '13'
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
name: Red Access
provenance_date: '2026-11-10'
provider_name: Red Access
provider_slug: redaccess
slug: redaccess-eligibility
source_date: '2026-11-10'
source_filename: redaccess-eligibility.yml
source_heading: Eligibility
source_page: https://redaccess.io/wp-content/uploads/2025/09/Terms.pdf
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Red Access\naid: redaccess\nurl: https://redaccess.io/wp-content/uploads/2025/09/Terms.pdf\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Site is only intended for individuals aged 13 years or older.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: The Site is only intended for individuals aged 13 years or older.\n"
source_yaml_url: https://artifacts.apis.io/redaccess/eligibility/redaccess-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from Red Access's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Security
- Cybersecurity
- Secure Service Edge
- Browser Security
- Zero Trust
- Data Loss Prevention
- SSE
---
