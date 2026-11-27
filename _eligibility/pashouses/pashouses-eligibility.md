---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - ID
    text: Layanan sesuai atau tersedia untuk digunakan di wilayah Negara Kesatuan Republik Indonesia.
  entity_types:
  - text: Setiap pengguna Situs adalah individu yang cakap dan bertanggung jawab untuk menggunakan Layanan Pashouses.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: False or misleading data
    text: Memberikan informasi Data maupun Data Pribadi yang palsu dan menyesatkan.
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
name: Pashouses
provenance_date: '2026-11-10'
provider_name: Pashouses
provider_slug: pashouses
slug: pashouses-eligibility
source_date: '2026-11-10'
source_filename: pashouses-eligibility.yml
source_heading: Eligibility
source_page: https://pashouses.id/terms-and-condition
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Pashouses\naid: pashouses\nurl: https://pashouses.id/terms-and-condition\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - ID\n  excluded: []\n  text: Layanan sesuai atau tersedia untuk digunakan di wilayah Negara Kesatuan Republik Indonesia.\nentity_types:\n- type: individual\n  text: Setiap pengguna Situs adalah individu yang cakap dan bertanggung jawab untuk menggunakan Layanan Pashouses.\nrestricted_uses:\n- summary: False or misleading data\n  text: Memberikan informasi Data maupun Data Pribadi yang palsu dan menyesatkan.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\n\
  minimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/pashouses/eligibility/pashouses-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Pashouses's own page on 2026-11-10.
synthetic: false
tags:
- Company
- PropTech
- Real Estate
- Indonesia
- Marketplace
- Mortgage
- iBuyer
---
