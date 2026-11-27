---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: 您在使用本服务时应遵守中华人民共和国相关法律法规（不包括香港特别行政区、澳门特别行政区和中国台湾地区法律）
  entity_types:
  - text: 所有使用 Ping++ 服务的主体（包括但不限于个人、公司等）
    type: individual
  - text: 所有使用 Ping++ 服务的主体（包括但不限于个人、公司等）
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Illegal purposes including money laundering
    text: 洗钱、非法套现、传销、贩卖枪支、毒品、禁药、盗版软件、淫秽物品或其他违禁物等
  - summary: Fraudulent transactions
    text: 利用 Ping++ 服务进行无真实交易背景的虚假交易的
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: 本公司有权在本公司认为的适当情形时要求验证核实您的有效身份证件或其他必要文件，且完成本公司要求的相关身份认证。
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Ping++
provenance_date: '2026-11-10'
provider_name: Ping++
provider_slug: ping
slug: ping-eligibility
source_date: '2026-11-10'
source_filename: ping-eligibility.yml
source_heading: Eligibility
source_page: https://www.pingxx.com/terms.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ping++\naid: ping\nurl: https://www.pingxx.com/terms.html\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: 您在使用本服务时应遵守中华人民共和国相关法律法规（不包括香港特别行政区、澳门特别行政区和中国台湾地区法律）\nentity_types:\n- type: individual\n  text: 所有使用 Ping++ 服务的主体（包括但不限于个人、公司等）\n- type: business\n  text: 所有使用 Ping++ 服务的主体（包括但不限于个人、公司等）\nrestricted_uses:\n- summary: Illegal purposes including money laundering\n  text: 洗钱、非法套现、传销、贩卖枪支、毒品、禁药、盗版软件、淫秽物品或其他违禁物等\n- summary: Fraudulent transactions\n  text: 利用 Ping++ 服务进行无真实交易背景的虚假交易的\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: 本公司有权在本公司认为的适当情形时要求验证核实您的有效身份证件或其他必要文件，且完成本公司要求的相关身份认证。\n\
  minimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/ping/eligibility/ping-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 6 quoted statements, read from Ping++'s own page on 2026-11-10.
synthetic: false
tags:
- Company
- Payments
- Aggregated Payment
- Fintech
- Payment Gateway
- Split Settlement
- WeChat Pay
- Alipay
- UnionPay
- China
- Payouts
---
