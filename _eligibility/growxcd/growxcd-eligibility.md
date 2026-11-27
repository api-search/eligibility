---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Use of the Site is available only to persons who can legally enter into contracts under applicable laws.
    type: individual
  minimum_age:
    text: null
    value: null
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
name: GrowXCD
provenance_date: '2026-11-09'
provider_name: GrowXCD
provider_slug: growxcd
slug: growxcd-eligibility
source_date: '2026-11-09'
source_filename: growxcd-eligibility.yml
source_heading: Eligibility
source_page: https://growxcd.com/assets/Pdf/Terms-and-Conditions.pdf
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: GrowXCD\naid: growxcd\nurl: https://growxcd.com/assets/Pdf/Terms-and-Conditions.pdf\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Use of the Site is available only to persons who can legally enter into contracts under applicable laws.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/growxcd/eligibility/growxcd-eligibility.yml
stated_fields:
- entity_types
summary_line: 1 quoted statement, read from GrowXCD's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Lending
- NBFC
- Financial Services
- India
- Loans
- Mortgage
---
