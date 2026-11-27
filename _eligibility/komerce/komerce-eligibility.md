---
api_specs:
- filename: komerce-cost-api-openapi.yml
  format: yaml
  label: Komerce Cost API
  slug: komerce-cost-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/komerce/openapi/komerce-cost-api-openapi.yml
- filename: komerce-destinations-api-openapi.yml
  format: yaml
  label: Komerce Destinations API
  slug: komerce-destinations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/komerce/openapi/komerce-destinations-api-openapi.yml
- filename: komerce-orders-api-openapi.yml
  format: yaml
  label: Komerce Orders API
  slug: komerce-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/komerce/openapi/komerce-orders-api-openapi.yml
- filename: komerce-payments-api-openapi.yml
  format: yaml
  label: Komerce Payments API
  slug: komerce-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/komerce/openapi/komerce-payments-api-openapi.yml
- filename: komerce-pickup-api-openapi.yml
  format: yaml
  label: Komerce Pickup API
  slug: komerce-pickup-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/komerce/openapi/komerce-pickup-api-openapi.yml
- filename: komerce-qris-api-openapi.yml
  format: yaml
  label: Komerce QRIS API
  slug: komerce-qris-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/komerce/openapi/komerce-qris-api-openapi.yml
- filename: komerce-tracking-api-openapi.yml
  format: yaml
  label: Komerce Tracking API
  slug: komerce-tracking-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/komerce/openapi/komerce-tracking-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Pengguna Jasa Komerce terdiri dari pebisnis yang melakukan transaksi melalui daring baik oleh perseorangan maupun perusahaan.
    type: individual
  - text: Kerjasama dapat dilakukan antara Komerce dengan pelaku bisnis baik perseorangan maupun perusahaan, lembaga, komunitas, dan pemerintah.
    type: business
  - text: Kerjasama dapat dilakukan antara Komerce dengan pelaku bisnis baik perseorangan maupun perusahaan, lembaga, komunitas, dan pemerintah.
    type: government
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful use of the sites and apps
    text: Penyalahgunaan situs, aplikasi Komerce dan Mitra Komerce untuk kepentingan pribadi maupun kelompok yang melanggar hukum akan ditindak
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: 4.1 User dan pengguna jasa Komerce wajib memberikan data yang diperlukan.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Komerce
provenance_date: '2026-11-09'
provider_name: Komerce
provider_slug: komerce
slug: komerce-eligibility
source_date: '2026-11-09'
source_filename: komerce-eligibility.yml
source_heading: Eligibility
source_page: https://komerce.id/syarat-ketentuan/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Komerce\naid: komerce\nurl: https://komerce.id/syarat-ketentuan/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Pengguna Jasa Komerce terdiri dari pebisnis yang melakukan transaksi melalui daring baik oleh perseorangan\n    maupun perusahaan.\n- type: business\n  text: Kerjasama dapat dilakukan antara Komerce dengan pelaku bisnis baik perseorangan maupun perusahaan, lembaga,\n    komunitas, dan pemerintah.\n- type: government\n  text: Kerjasama dapat dilakukan antara Komerce dengan pelaku bisnis baik perseorangan maupun perusahaan,\
  \ lembaga,\n    komunitas, dan pemerintah.\nrestricted_uses:\n- summary: Unlawful use of the sites and apps\n  text: Penyalahgunaan situs, aplikasi Komerce dan Mitra Komerce untuk kepentingan pribadi maupun kelompok yang\n    melanggar hukum akan ditindak\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: 4.1 User dan pengguna jasa Komerce wajib memberikan data yang diperlukan.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/komerce/eligibility/komerce-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 5 quoted statements, read from Komerce's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Shipping
- Logistics
- E-Commerce
- Payments
- QRIS
- Indonesia
- Couriers
- Tracking
- Fulfillment
---
