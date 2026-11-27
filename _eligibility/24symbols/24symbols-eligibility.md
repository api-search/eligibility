---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: you confirm that you are 18 years of age or more, that you are 16 years of age or more or that you have received your parent’s or guardian’s consent to enter into this Agreement
    type: individual
  minimum_age:
    text: you are 16 years of age or more or that you have received your parent’s or guardian’s consent
    value: '16'
  restricted_uses:
  - summary: Personal, non-commercial use only
    text: You are granted a limited, non-exclusive, revocable license to make personal, non-commercial use of 24symbols
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
name: 24Symbols
provenance_date: '2026-11-09'
provider_name: 24Symbols
provider_slug: 24symbols
slug: 24symbols-eligibility
source_date: '2026-11-09'
source_filename: 24symbols-eligibility.yml
source_heading: Eligibility
source_page: https://www.24symbols.com/license_agreement
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: 24Symbols\naid: 24symbols\nurl: https://www.24symbols.com/license_agreement\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: you confirm that you are 18 years of age or more, that you are 16 years of age or more or that you have\n    received your parent’s or guardian’s consent to enter into this Agreement\nrestricted_uses:\n- summary: Personal, non-commercial use only\n  text: You are granted a limited, non-exclusive, revocable license to make personal, non-commercial use of 24symbols\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: '16'\n  text: you are 16 years of age or more or that you have received your parent’s or guardian’s consent\n"
source_yaml_url: https://artifacts.apis.io/24symbols/eligibility/24symbols-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from 24Symbols's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Books
- Ebooks
- Reading
- Digital Library
- Subscription
- Media
- Publishing
- Entertainment
- Content
---
