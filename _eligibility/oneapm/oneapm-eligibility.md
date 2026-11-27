---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 注册、登录、下载、使用、浏览本公司产品、服务的个人或组织
    type: other
  minimum_age:
    text: 未成年人应在法定监护人陪同下阅读
    value: null
  restricted_uses:
  - summary: Competing service access
    text: 您不得以创建相同或竞争服务为目的访问本网站或使用本公司产品、程序及服务
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: 您必须注册相应账户并且于注册页面上提供相关的个人信息
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: OneAPM
provenance_date: '2026-11-10'
provider_name: OneAPM
provider_slug: oneapm
slug: oneapm-eligibility
source_date: '2026-11-10'
source_filename: oneapm-eligibility.yml
source_heading: Eligibility
source_page: https://www.oneapm.com/privacy_policy.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: OneAPM\naid: oneapm\nurl: https://www.oneapm.com/privacy_policy.html\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: other\n  text: 注册、登录、下载、使用、浏览本公司产品、服务的个人或组织\nrestricted_uses:\n- summary: Competing service access\n  text: 您不得以创建相同或竞争服务为目的访问本网站或使用本公司产品、程序及服务\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: 您必须注册相应账户并且于注册页面上提供相关的个人信息\nminimum_age:\n  value: null\n  text: 未成年人应在法定监护人陪同下阅读\n"
source_yaml_url: https://artifacts.apis.io/oneapm/eligibility/oneapm-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from OneAPM's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Application Performance Management
- APM
- Observability
- Monitoring
- AIOps
- IT Operations
- Log Analytics
- Real User Monitoring
- Software-as-a-Service
---
