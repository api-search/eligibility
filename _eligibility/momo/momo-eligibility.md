---
api_specs:
- filename: postman.yaml
  format: yaml
  label: MoMo All-in-One Payment Gateway (AIO v2)
  slug: aio-payment-gateway
  spec_type: Postman
  url: https://developers.momo.vn/v3/docs/payment/api/other/postman/
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: là người dùng trực tiếp đứng tên đăng ký mở và sử dụng Tài Khoản MoMo/Tài Khoản Ví Điện Tử
    type: individual
  minimum_age:
    text: từ đủ 15 tuổi đến chưa đủ 18 tuổi
    value: '15'
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: định danh và Xác Thực Sinh Trắc Học theo quy định của Ngân hàng Nhà nước
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: MoMo
provenance_date: '2026-11-10'
provider_name: MoMo
provider_slug: momo
slug: momo-eligibility
source_date: '2026-11-10'
source_filename: momo-eligibility.yml
source_heading: Eligibility
source_page: https://www.momo.vn/dieu-khoan-dieu-le
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: MoMo\naid: momo\nurl: https://www.momo.vn/dieu-khoan-dieu-le\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: là người dùng trực tiếp đứng tên đăng ký mở và sử dụng Tài Khoản MoMo/Tài Khoản Ví Điện Tử\nrestricted_uses: []\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: định danh và Xác Thực Sinh Trắc Học theo quy định của Ngân hàng Nhà nước\nminimum_age:\n  value: '15'\n  text: từ đủ 15 tuổi đến chưa đủ 18 tuổi\n"
source_yaml_url: https://artifacts.apis.io/momo/eligibility/momo-eligibility.yml
stated_fields:
- entity_types
- verification
- minimum_age
summary_line: 3 quoted statements, read from MoMo's own page on 2026-11-10.
synthetic: false
tags:
- Payments
- Mobile Payments
- Fintech
- Digital Wallet
- Payment Gateway
- QR Payments
- Disbursements
- Buy Now Pay Later
- E-Commerce
- Vietnam
---
