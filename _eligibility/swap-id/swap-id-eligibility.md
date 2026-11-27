---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: merujuk pada individu yang meregistrasi, masuk dan menggunakan layanan ini
    type: individual
  minimum_age:
    text: pemakaian layanan ini dilarang untuk orang di bawah usia 17 tahun
    value: '17'
  restricted_uses:
  - summary: Non-commercial use only for the app licence
    text: untuk tujuan non-komersial
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: menyelesaikan semua prosedur verifikasi sesuai identitas
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: swap
provenance_date: '2026-11-10'
provider_name: swap
provider_slug: swap-id
slug: swap-id-eligibility
source_date: '2026-11-10'
source_filename: swap-id-eligibility.yml
source_heading: Eligibility
source_page: https://www.swap.id/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: swap\naid: swap-id\nurl: https://www.swap.id/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: merujuk pada individu yang meregistrasi, masuk dan menggunakan layanan ini\nrestricted_uses:\n- summary: Non-commercial use only for the app licence\n  text: untuk tujuan non-komersial\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: menyelesaikan semua prosedur verifikasi sesuai identitas\nminimum_age:\n  value: '17'\n  text: pemakaian layanan ini dilarang untuk orang di bawah usia 17 tahun\n"
source_yaml_url: https://artifacts.apis.io/swap-id/eligibility/swap-id-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from swap's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Energy
- Mobility
- Battery
- Infrastructure
- IoT
---
