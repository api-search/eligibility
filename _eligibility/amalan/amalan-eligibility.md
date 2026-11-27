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
  - summary: Eligible debt types and minimum amount
    text: Untuk saat ini, kami hanya dapat melayani jenis utang kartu kredit/KTA di bank konvensional dan/atau pinjaman online (pinjol) legal & berizin OJK dengan total minimum 10 juta rupiah, dan/atau KPR/KMG jaminan rumah.
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
name: Amalan
provenance_date: '2026-11-09'
provider_name: Amalan
provider_slug: amalan
slug: amalan-eligibility
source_date: '2026-11-09'
source_filename: amalan-eligibility.yml
source_heading: Eligibility
source_page: https://blog.amalan.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Amalan\naid: amalan\nurl: https://blog.amalan.com/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Eligible debt types and minimum amount\n  text: Untuk saat ini, kami hanya dapat melayani jenis utang kartu kredit/KTA di bank konvensional dan/atau pinjaman\n    online (pinjol) legal & berizin OJK dengan total minimum 10 juta rupiah, dan/atau KPR/KMG jaminan rumah.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/amalan/eligibility/amalan-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Amalan's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Financial Services
- Fintech
- Debt Management
- Lending
- Credit Score
- Consumer
- Indonesia
---
