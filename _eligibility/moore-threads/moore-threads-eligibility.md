---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 您应当是具有完全民事行为能力的自然人
    type: individual
  - text: 如您是企业用户，则在您注册及使用夸娥云产品/服务时，您应当是合法成立并有效存续的法人或非法人组织
    type: business
  minimum_age:
    text: 您应当是年满18周岁且具备民事行为能力的自然人
    value: '18'
  restricted_uses:
  - summary: Prohibited input and output content categories
    text: 您不得向夸娥云产品/服务输入且不得通过输入诱导其输出以下内容
  - summary: Use to infringe rights or commit fraud
    text: 以侵犯任何人权利的方式使用夸娥云产品/服务，用于非法收集使用他人信息、欺诈、诈骗
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: 您应按照国家相关法律法规的规定实名注册并登录后方可使用
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Moore Threads
provenance_date: '2026-11-10'
provider_name: Moore Threads
provider_slug: moore-threads
slug: moore-threads-eligibility
source_date: '2026-11-10'
source_filename: moore-threads-eligibility.yml
source_heading: Eligibility
source_page: https://docs.mthreads.com/kuaecloud/kuaecloud-doc-online/terms/user_agreement/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Moore Threads\naid: moore-threads\nurl: https://docs.mthreads.com/kuaecloud/kuaecloud-doc-online/terms/user_agreement/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: 您应当是具有完全民事行为能力的自然人\n- type: business\n  text: 如您是企业用户，则在您注册及使用夸娥云产品/服务时，您应当是合法成立并有效存续的法人或非法人组织\nrestricted_uses:\n- summary: Prohibited input and output content categories\n  text: 您不得向夸娥云产品/服务输入且不得通过输入诱导其输出以下内容\n- summary: Use to infringe rights or commit fraud\n  text: 以侵犯任何人权利的方式使用夸娥云产品/服务，用于非法收集使用他人信息、欺诈、诈骗\nverification:\n  kyc: true\n  kyb: null\n  approval_required:\
  \ null\n  text: 您应按照国家相关法律法规的规定实名注册并登录后方可使用\nminimum_age:\n  value: '18'\n  text: 您应当是年满18周岁且具备民事行为能力的自然人\n"
source_yaml_url: https://artifacts.apis.io/moore-threads/eligibility/moore-threads-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Moore Threads's own page on 2026-11-10.
synthetic: false
tags:
- Company
- GPU
- Artificial Intelligence
- Machine Learning
- Semiconductors
- Speech Recognition
- Text-to-Speech
- Voice
- Inference
- Cloud Computing
- Developer Tools
- China
---
