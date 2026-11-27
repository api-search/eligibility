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
  - summary: Transfers blocked where special benefits or transfer fees apply
    text: If this is the case, we will not transfer your pension, as you may be better off not transferring in these cases.
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
name: Penny
provenance_date: '2026-11-10'
provider_name: Penny
provider_slug: penny
slug: penny-eligibility
source_date: '2026-11-10'
source_filename: penny-eligibility.yml
source_heading: Eligibility
source_page: https://pennypension.com/legal/terms-and-documents
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Penny\naid: penny\nurl: https://pennypension.com/legal/terms-and-documents\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Transfers blocked where special benefits or transfer fees apply\n  text: If this is the case, we will not transfer your pension, as you may be better off not transferring in these\n    cases.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/penny/eligibility/penny-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Penny's own page on 2026-11-10.
synthetic: false
tags:
- Fintech
- Retirement
- Pensions
- Mobile App
- Financial Planning
---
