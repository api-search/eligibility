---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Anda harus berkomitmen terhadap batasan usia untuk melakukan pendaftaran akun, yaitu Anda harus berusia minimal 18 tahun
    type: individual
  minimum_age:
    text: Anda harus berusia minimal 18 tahun
    value: '18'
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: Kami dapat mengakses Kamera dan Audio pada perangkat seluler Pengguna untuk kami dapat menyediakan Layanan yang akan diberikan kepada Anda, termasuk keperluan verifikasi identitas Anda.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Finku
provenance_date: '2026-11-09'
provider_name: Finku
provider_slug: finku
slug: finku-eligibility
source_date: '2026-11-09'
source_filename: finku-eligibility.yml
source_heading: Eligibility
source_page: https://finku.id/id/terms-and-privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Finku\naid: finku\nurl: https://finku.id/id/terms-and-privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Anda harus berkomitmen terhadap batasan usia untuk melakukan pendaftaran akun, yaitu Anda harus berusia\n    minimal 18 tahun\nrestricted_uses: []\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: Kami dapat mengakses Kamera dan Audio pada perangkat seluler Pengguna untuk kami dapat menyediakan Layanan\n    yang akan diberikan kepada Anda, termasuk keperluan verifikasi identitas Anda.\nminimum_age:\n\
  \  value: '18'\n  text: Anda harus berusia minimal 18 tahun\n"
source_yaml_url: https://artifacts.apis.io/finku/eligibility/finku-eligibility.yml
stated_fields:
- entity_types
- verification
- minimum_age
summary_line: 3 quoted statements, read from Finku's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Personal Finance
- Fintech
- Budgeting
- Expense Tracking
- Money Management
- Financial Analytics
- AI Assistant
- Indonesia
- Consumer
---
