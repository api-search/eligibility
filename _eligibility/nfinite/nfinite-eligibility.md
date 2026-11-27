---
claim_count: 4
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - KP
    - SD
    - SY
    served: []
    text: a U.S. embargoed country (currently Cuba, Iran, North Korea, Sudan and Syria)
  entity_types:
  - text: THIS IS A LEGAL AGREEMENT BETWEEN YOU AND THE LEGAL ENTITY YOU REPRESENT
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Sanctions and export compliance
    text: Customer agrees that it will not import, export, re-export, transfer or otherwise use Nfinite Proprietary Materials in violation of these laws and regulations
  - summary: Unlawful or harmful content
    text: any racist, hateful, abusive, defamatory, obscene or discriminatory content
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- CU
- IR
- KP
- SD
- SY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Nfinite
provenance_date: '2026-11-10'
provider_name: Nfinite
provider_slug: nfinite
slug: nfinite-eligibility
source_date: '2026-11-10'
source_filename: nfinite-eligibility.yml
source_heading: Eligibility
source_page: https://nfinite.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Nfinite\naid: nfinite\nurl: https://nfinite.ai/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  - SD\n  - SY\n  text: a U.S. embargoed country (currently Cuba, Iran, North Korea, Sudan and Syria)\nentity_types:\n- type: business\n  text: THIS IS A LEGAL AGREEMENT BETWEEN YOU AND THE LEGAL ENTITY YOU REPRESENT\nrestricted_uses:\n- summary: Sanctions and export compliance\n  text: Customer agrees that it will not import, export, re-export, transfer or otherwise use Nfinite Proprietary\n    Materials in violation of these laws and regulations\n- summary: Unlawful\
  \ or harmful content\n  text: any racist, hateful, abusive, defamatory, obscene or discriminatory content\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/nfinite/eligibility/nfinite-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from Nfinite's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Visual Intelligence
- Digital Shelf
- Product Imagery
- Retail
- E-Commerce
- Artificial Intelligence
- Content Generation
---
