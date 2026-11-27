---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Merchant adalah individu atau badan usaha penyedia barang atau jasa yang merupakan pengguna Layanan
    type: individual
  - text: Mitra Usaha adalah badan usaha penyedia layanan Point of Sales ( POS ), Food Aggregator Services dan/atau badan usaha dengan jasa lainnya
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Device-limited software use
    text: untuk digunakan hanya pada perangkat telepon genggam, tablet, perangkat POS atau aplikasi aman ( secure ) berbasis situs web dan/atau perangkat lainnya yang Kami tentukan dari waktu ke waktu
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Dengan terlebih dahulu mendaftarkan diri sebagai pengguna Aplikasi GoBiz dan dengan tunduk pada ketentuan penggunaan sistem sebagaimana ditunjukan dalam Platform ini, Anda dapat melakukan proses demonstrasi sandbox secara mandiri
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: GoJek
provenance_date: '2026-11-09'
provider_name: GoJek
provider_slug: gojek
slug: gojek-eligibility
source_date: '2026-11-09'
source_filename: gojek-eligibility.yml
source_heading: Eligibility
source_page: https://app.gobiz.com/files/terms-and-condition/gobiz-developer-portal-v01.2022
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: GoJek\naid: gojek\nurl: https://app.gobiz.com/files/terms-and-condition/gobiz-developer-portal-v01.2022\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Merchant adalah individu atau badan usaha penyedia barang atau jasa yang merupakan pengguna Layanan\n- type: business\n  text: Mitra Usaha adalah badan usaha penyedia layanan Point of Sales ( POS ), Food Aggregator Services dan/atau\n    badan usaha dengan jasa lainnya\nrestricted_uses:\n- summary: Device-limited software use\n  text: untuk digunakan hanya pada perangkat telepon genggam,\
  \ tablet, perangkat POS atau aplikasi aman ( secure\n    ) berbasis situs web dan/atau perangkat lainnya yang Kami tentukan dari waktu ke waktu\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Dengan terlebih dahulu mendaftarkan diri sebagai pengguna Aplikasi GoBiz dan dengan tunduk pada ketentuan\n    penggunaan sistem sebagaimana ditunjukan dalam Platform ini, Anda dapat melakukan proses demonstrasi sandbox\n    secara mandiri\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/gojek/eligibility/gojek-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from GoJek's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Super App
- Ride Hailing
- Food Delivery
- Point-of-Sale
- Merchant Platform
- Payments
- QRIS
- Logistics
- Indonesia
- Southeast Asia
- Webhook
- OAuth
- Authentication
---
