---
api_specs:
- filename: biver-id-openapi-generated.yml
  format: yaml
  label: Biver API
  slug: biver-id-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/biver-id/openapi/_ae-authored/biver-id-openapi-generated.yml
claim_count: 7
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Anda harus berusia minimal 18 tahun untuk mendaftar.
    type: individual
  - text: Jika Anda menggunakan layanan atas nama organisasi atau badan hukum, Anda menyatakan memiliki kewenangan untuk mengikat organisasi tersebut pada Syarat dan Ketentuan ini.
    type: business
  minimum_age:
    text: Anda harus berusia minimal 18 tahun untuk mendaftar.
    value: 18 tahun
  restricted_uses:
  - summary: Online gambling
    text: Perjudian online — termasuk casino, sports betting, togel, slot, poker online, dan afiliasi perjudian.
  - summary: Pornography and adult content
    text: Pornografi dan konten dewasa — sesuai UU No. 44 Tahun 2008 tentang Pornografi.
  - summary: Narcotics and banned substances
    text: Narkotika dan zat terlarang — sesuai UU No. 35 Tahun 2009 tentang Narkotika.
  - summary: Terrorism and extremism
    text: Terorisme dan ekstremisme — sesuai UU No. 5 Tahun 2018 tentang Pemberantasan Tindak Pidana Terorisme.
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
name: Biver
provenance_date: '2026-11-09'
provider_name: Biver
provider_slug: biver-id
slug: biver-id-eligibility
source_date: '2026-11-09'
source_filename: biver-id-eligibility.yml
source_heading: Eligibility
source_page: https://biver.id/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Biver\naid: biver-id\nurl: https://biver.id/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Anda harus berusia minimal 18 tahun untuk mendaftar.\n- type: business\n  text: Jika Anda menggunakan layanan atas nama organisasi atau badan hukum, Anda menyatakan memiliki kewenangan\n    untuk mengikat organisasi tersebut pada Syarat dan Ketentuan ini.\nrestricted_uses:\n- summary: Online gambling\n  text: Perjudian online — termasuk casino, sports betting, togel, slot, poker online, dan afiliasi perjudian.\n- summary: Pornography and\
  \ adult content\n  text: Pornografi dan konten dewasa — sesuai UU No. 44 Tahun 2008 tentang Pornografi.\n- summary: Narcotics and banned substances\n  text: Narkotika dan zat terlarang — sesuai UU No. 35 Tahun 2009 tentang Narkotika.\n- summary: Terrorism and extremism\n  text: Terorisme dan ekstremisme — sesuai UU No. 5 Tahun 2018 tentang Pemberantasan Tindak Pidana Terorisme.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: 18 tahun\n  text: Anda harus berusia minimal 18 tahun untuk mendaftar.\n"
source_yaml_url: https://artifacts.apis.io/biver-id/eligibility/biver-id-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 7 quoted statements, read from Biver's own page on 2026-11-09.
synthetic: false
tags:
- E-Commerce
- Artificial Intelligence
- Landing Page Builder
- Indonesia
- UMKM
---
