---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Pengguna atau Anda merujuk pada setiap individu yang mengakses dan/atau menggunakan Platform
    type: individual
  - text: Apabila Anda melakukan pendaftaran atas nama suatu badan usaha
    type: business
  minimum_age:
    text: Anda berusia minimal 21 tahun atau sudah menikah dan tidak sedang di bawah perwalian
    value: '21'
  restricted_uses:
  - summary: Not for emergencies
    text: Layanan Chat Bersama Dokter tidak diperuntukkan bagi kondisi gawat darurat atau kejadian medis akut yang memerlukan tindakan segera
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: ALODOKTER berhak melakukan proses verifikasi identitas secara berkala atau sewaktu-waktu
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Alodokter
provenance_date: '2026-11-09'
provider_name: Alodokter
provider_slug: alodokter
slug: alodokter-eligibility
source_date: '2026-11-09'
source_filename: alodokter-eligibility.yml
source_heading: Eligibility
source_page: https://www.alodokter.com/syarat-dan-ketentuan
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Alodokter\naid: alodokter\nurl: https://www.alodokter.com/syarat-dan-ketentuan\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Pengguna atau Anda merujuk pada setiap individu yang mengakses dan/atau menggunakan Platform\n- type: business\n  text: Apabila Anda melakukan pendaftaran atas nama suatu badan usaha\nrestricted_uses:\n- summary: Not for emergencies\n  text: Layanan Chat Bersama Dokter tidak diperuntukkan bagi kondisi gawat darurat atau kejadian medis akut yang\n    memerlukan tindakan segera\nverification:\n\
  \  kyc: true\n  kyb: null\n  approval_required: null\n  text: ALODOKTER berhak melakukan proses verifikasi identitas secara berkala atau sewaktu-waktu\nminimum_age:\n  value: '21'\n  text: Anda berusia minimal 21 tahun atau sudah menikah dan tidak sedang di bawah perwalian\n"
source_yaml_url: https://artifacts.apis.io/alodokter/eligibility/alodokter-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Alodokter's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Health
- Healthcare
- Telehealth
- Digital Health
- Medical
- Doctors
- Insurance
- Indonesia
---
