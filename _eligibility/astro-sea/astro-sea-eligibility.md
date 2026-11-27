---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Pengguna adalah setiap individu yang menggunakan Aplikasi
    type: individual
  minimum_age:
    text: Pengguna wajib berusia sekurang-kurangnya 18 (delapan belas) tahun untuk dapat menggunakan Aplikasi ASTRO.
    value: '18'
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
name: Astro Sea
provenance_date: '2026-11-09'
provider_name: Astro Sea
provider_slug: astro-sea
slug: astro-sea-eligibility
source_date: '2026-11-09'
source_filename: astro-sea-eligibility.yml
source_heading: Eligibility
source_page: https://www.astronauts.id/sites/syarat-ketentuan
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Astro Sea\naid: astro-sea\nurl: https://www.astronauts.id/sites/syarat-ketentuan\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Pengguna adalah setiap individu yang menggunakan Aplikasi\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Pengguna wajib berusia sekurang-kurangnya 18 (delapan belas) tahun untuk dapat menggunakan Aplikasi ASTRO.\n"
source_yaml_url: https://artifacts.apis.io/astro-sea/eligibility/astro-sea-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from Astro Sea's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Quick Commerce
- E-Commerce
- Grocery Delivery
- Retail
- Consumer
- Indonesia
- Mobile App
---
