---
api_specs:
- filename: doku-access-token-api-openapi.yml
  format: yaml
  label: DOKU Access Token API
  slug: doku-access-token-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/doku/openapi/doku-access-token-api-openapi.yml
- filename: doku-checkout-api-openapi.yml
  format: yaml
  label: DOKU Checkout API
  slug: doku-checkout-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/doku/openapi/doku-checkout-api-openapi.yml
- filename: doku-direct-debit-e-wallet-api-openapi.yml
  format: yaml
  label: DOKU Direct Debit & e-Wallet API
  slug: doku-direct-debit-e-wallet-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/doku/openapi/doku-direct-debit-e-wallet-api-openapi.yml
- filename: doku-payout-api-openapi.yml
  format: yaml
  label: DOKU Payout API
  slug: doku-payout-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/doku/openapi/doku-payout-api-openapi.yml
- filename: doku-qris-api-openapi.yml
  format: yaml
  label: DOKU QRIS API
  slug: doku-qris-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/doku/openapi/doku-qris-api-openapi.yml
- filename: doku-virtual-account-api-openapi.yml
  format: yaml
  label: DOKU Virtual Account API
  slug: doku-virtual-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/doku/openapi/doku-virtual-account-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - ID
    text: Setiap pihak yang berada di wilayah Negara Kesatuan Republik Indonesia dapat mengakses Platform / DOKU Dashboard
  entity_types:
  - text: 'Merchant perorangan: 5 transaksi atau senilai Rp1.000.000 (satu juta rupiah)'
    type: individual
  - text: Informasi untuk Merchant perusahaan dalam negeri
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Prohibited product categories
    text: Produk yang mengandung materi pornografi; judi atau pertaruhan; perdagangan manusia atau perdagangan spesies langka yang dilindungi; persenjataan, peralatan militer, dan bahan peledak.
  verification:
    approval_required: true
    kyb: true
    kyc: true
    text: PERUSAHAAN SEBAGAI PENYEDIA JASA PEMBAYARAN WAJIB MEMILIKI DAN MENJALANKAN MEKANISME DAN PROSEDUR VERIFIKASI AKUN SEHUBUNGAN DENGAN PENYEDIAAN LAYANAN YANG DISELENGGARAKAN.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: DOKU
provenance_date: '2026-11-09'
provider_name: DOKU
provider_slug: doku
slug: doku-eligibility
source_date: '2026-11-09'
source_filename: doku-eligibility.yml
source_heading: Eligibility
source_page: https://dashboard.doku.com/doku-agreement/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: DOKU\naid: doku\nurl: https://dashboard.doku.com/doku-agreement/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - ID\n  excluded: []\n  text: Setiap pihak yang berada di wilayah Negara Kesatuan Republik Indonesia dapat mengakses Platform / DOKU Dashboard\nentity_types:\n- type: individual\n  text: 'Merchant perorangan: 5 transaksi atau senilai Rp1.000.000 (satu juta rupiah)'\n- type: business\n  text: Informasi untuk Merchant perusahaan dalam negeri\nrestricted_uses:\n- summary: Prohibited product categories\n  text: Produk yang mengandung materi pornografi; judi atau\
  \ pertaruhan; perdagangan manusia atau perdagangan spesies\n    langka yang dilindungi; persenjataan, peralatan militer, dan bahan peledak.\nverification:\n  kyc: true\n  kyb: true\n  approval_required: true\n  text: PERUSAHAAN SEBAGAI PENYEDIA JASA PEMBAYARAN WAJIB MEMILIKI DAN MENJALANKAN MEKANISME DAN PROSEDUR VERIFIKASI\n    AKUN SEHUBUNGAN DENGAN PENYEDIAAN LAYANAN YANG DISELENGGARAKAN.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/doku/eligibility/doku-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 5 quoted statements, read from DOKU's own page on 2026-11-09.
synthetic: false
tags:
- Payments
- Payment Gateway
- Fintech
- Indonesia
- SEA
- SNAP
- Virtual Accounts
- Digital Wallet
- QRIS
- Direct Debit
- Payouts
---
