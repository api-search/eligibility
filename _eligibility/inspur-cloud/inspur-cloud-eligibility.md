---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 您及您所代表的企业（以下统称为“您”）因经营需要购买浪潮云
    type: business
  minimum_age:
    text: 如您未满18周岁，请在法定监护人的陪同下阅读本用户协议条款。
    value: '18'
  verification:
    approval_required: true
    kyb: true
    kyc: true
    text: 为保证账户和交易安全，浪潮云有权随时要求您完成浪潮云账户的实名认证并要求您提供相应的证明资料，包括但不限于身份证件、工商登记证件、联系方式、联系人等
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Inspur Cloud
provenance_date: '2026-11-09'
provider_name: Inspur Cloud
provider_slug: inspur-cloud
slug: inspur-cloud-eligibility
source_date: '2026-11-09'
source_filename: inspur-cloud-eligibility.yml
source_heading: Eligibility
source_page: https://console1.cloud.inspur.com/document/declaration/protocol/client/client.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Inspur Cloud\naid: inspur-cloud\nurl: https://console1.cloud.inspur.com/document/declaration/protocol/client/client.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: 您及您所代表的企业（以下统称为“您”）因经营需要购买浪潮云\nrestricted_uses: []\nverification:\n  kyc: true\n  kyb: true\n  approval_required: true\n  text: 为保证账户和交易安全，浪潮云有权随时要求您完成浪潮云账户的实名认证并要求您提供相应的证明资料，包括但不限于身份证件、工商登记证件、联系方式、联系人等\nminimum_age:\n  value: '18'\n  text: 如您未满18周岁，请在法定监护人的陪同下阅读本用户协议条款。\n"
source_yaml_url: https://artifacts.apis.io/inspur-cloud/eligibility/inspur-cloud-eligibility.yml
stated_fields:
- entity_types
- verification
- minimum_age
summary_line: 3 quoted statements, read from Inspur Cloud's own page on 2026-11-09.
synthetic: false
tags:
- Cloud
- Infrastructure
- Compute
- Storage
- Networking
- Object Storage
- Identity
- Database
- Containers
- IoT
- Blockchain
- China
- Company
---
