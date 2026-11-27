---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful or harmful content
    text: 其他违反法律法规、部门规章或国家政策的内容。
  - summary: Cross-border transfer of personal information
    text: 不向中华人民共和国境外（为免疑义，包含香港特别行政区、澳门特别行政区及台湾地区）传输任何个人信息
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: 部分服务需要您提供真实身份信息完成实名认证，如您拒绝实名认证的，七牛云将无法为您提供该等服务。
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Qiniu Cloud
provenance_date: '2026-11-10'
provider_name: Qiniu Cloud
provider_slug: qiniu
slug: qiniu-eligibility
source_date: '2026-11-10'
source_filename: qiniu-eligibility.yml
source_heading: Eligibility
source_page: https://www.qiniu.com/agreements/user-agreement
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Qiniu Cloud\naid: qiniu\nurl: https://www.qiniu.com/agreements/user-agreement\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful or harmful content\n  text: 其他违反法律法规、部门规章或国家政策的内容。\n- summary: Cross-border transfer of personal information\n  text: 不向中华人民共和国境外（为免疑义，包含香港特别行政区、澳门特别行政区及台湾地区）传输任何个人信息\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: 部分服务需要您提供真实身份信息完成实名认证，如您拒绝实名认证的，七牛云将无法为您提供该等服务。\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/qiniu/eligibility/qiniu-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 3 quoted statements, read from Qiniu Cloud's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Cloud
- Object Storage
- CDN
- Media Processing
- Live Streaming
- SDK
- Artificial Intelligence
- China
---
