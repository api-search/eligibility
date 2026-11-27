---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Bạn được dùng Dịch vụ cho mục đích cá nhân, phi thương mại, trừ khi có thoả thuận khác bằng văn bản với Algolab.
    type: individual
  minimum_age:
    text: Bạn phải từ đủ 18 tuổi và cung cấp thông tin đúng sự thật.
    value: '18'
  restricted_uses:
  - summary: Commercial use without licence
    text: Dùng bất kỳ phần nào của Nội dung, kể cả dữ liệu thị trường và biểu đồ của nhà cung cấp thứ ba, cho mục đích thương mại khi chưa có giấy phép cần thiết từ chủ sở hữu tương ứng.
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
name: Algolab
provenance_date: '2026-11-09'
provider_name: Algolab
provider_slug: algolab-vn
slug: algolab-vn-eligibility
source_date: '2026-11-09'
source_filename: algolab-vn-eligibility.yml
source_heading: Eligibility
source_page: https://algolab.vn/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Algolab\naid: algolab-vn\nurl: https://algolab.vn/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Bạn được dùng Dịch vụ cho mục đích cá nhân, phi thương mại, trừ khi có thoả thuận khác bằng văn bản với\n    Algolab.\nrestricted_uses:\n- summary: Commercial use without licence\n  text: Dùng bất kỳ phần nào của Nội dung, kể cả dữ liệu thị trường và biểu đồ của nhà cung cấp thứ ba, cho mục\n    đích thương mại khi chưa có giấy phép cần thiết từ chủ sở hữu tương ứng.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: '18'\n  text: Bạn phải từ đủ 18 tuổi và cung cấp thông tin đúng sự thật.\n"
source_yaml_url: https://artifacts.apis.io/algolab-vn/eligibility/algolab-vn-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Algolab's own page on 2026-11-09.
synthetic: false
tags:
- Finance
- Data
- Artificial Intelligence
- Vietnam
- Stock Market
---
