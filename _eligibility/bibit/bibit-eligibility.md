---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - ID
    text: Warga Negara Indonesia (WNI), penduduk Republik Indonesia
  entity_types:
  - text: Nasabah adalah Individu yang terdaftar pada Bibit.
    type: individual
  minimum_age:
    text: Berusia 17 tahun atau lebih
    value: '17'
  restricted_uses:
  - summary: No use for others or account sales
    text: Nasabah tidak akan membuka rekening untuk kepentingan orang lain, memperjualbelikan rekening kepada pihak lain, dan/atau menggunakan rekening dengan tujuan dan/atau cara-cara yang melanggar hukum.
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
name: Bibit
provenance_date: '2026-11-09'
provider_name: Bibit
provider_slug: bibit
slug: bibit-eligibility
source_date: '2026-11-09'
source_filename: bibit-eligibility.yml
source_heading: Eligibility
source_page: https://bibit.id/term
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bibit\naid: bibit\nurl: https://bibit.id/term\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - ID\n  excluded: []\n  text: Warga Negara Indonesia (WNI), penduduk Republik Indonesia\nentity_types:\n- type: individual\n  text: Nasabah adalah Individu yang terdaftar pada Bibit.\nrestricted_uses:\n- summary: No use for others or account sales\n  text: Nasabah tidak akan membuka rekening untuk kepentingan orang lain, memperjualbelikan rekening kepada pihak\n    lain, dan/atau menggunakan rekening dengan tujuan dan/atau cara-cara yang melanggar hukum.\nverification:\n  kyc: null\n  kyb: null\n\
  \  approval_required: null\n  text: null\nminimum_age:\n  value: '17'\n  text: Berusia 17 tahun atau lebih\n"
source_yaml_url: https://artifacts.apis.io/bibit/eligibility/bibit-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Bibit's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Investment
- Mutual Funds
- Wealth Management
- Indonesia
- Consumer Finance
---
