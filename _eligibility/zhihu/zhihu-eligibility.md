---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 机构用户同意遵守 知乎机构号服务协议 以及 知乎机构号使用规范（试行）
    type: business
  minimum_age:
    text: 如果监护人希望未满 14 周岁的未成年人使用知乎，请务必为其开启青少年模式，知乎仅在青少年模式下向未满 14 周岁的未成年人提供产品或服务。
    value: null
  restricted_uses:
  - summary: Prohibited content
    text: 您不得利用本平台制作、上载、复制、发布、传播、转载或者以各种关键词/表述尝试输入或搜索如下内容
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: 在使用某些功能和/或某些单项服务前，如发布内容、直播开播等，您需要注册或登录知乎账号，并按照国家相关法律法规的要求完成真实身份信息认证。
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Zhihu
provenance_date: '2026-11-10'
provider_name: Zhihu
provider_slug: zhihu
slug: zhihu-eligibility
source_date: '2026-11-10'
source_filename: zhihu-eligibility.yml
source_heading: Eligibility
source_page: https://www.zhihu.com/term/zhihu-terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Zhihu\naid: zhihu\nurl: https://www.zhihu.com/term/zhihu-terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: 机构用户同意遵守 知乎机构号服务协议 以及 知乎机构号使用规范（试行）\nrestricted_uses:\n- summary: Prohibited content\n  text: 您不得利用本平台制作、上载、复制、发布、传播、转载或者以各种关键词/表述尝试输入或搜索如下内容\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: 在使用某些功能和/或某些单项服务前，如发布内容、直播开播等，您需要注册或登录知乎账号，并按照国家相关法律法规的要求完成真实身份信息认证。\nminimum_age:\n  value: null\n  text: 如果监护人希望未满 14 周岁的未成年人使用知乎，请务必为其开启青少年模式，知乎仅在青少年模式下向未满 14 周岁的未成年人提供产品或服务。\n"
source_yaml_url: https://artifacts.apis.io/zhihu/eligibility/zhihu-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Zhihu's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Media Entertainment
- Q&A
- Knowledge Sharing
- Community
- Content Platform
- Social
- China
---
