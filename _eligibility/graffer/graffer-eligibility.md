---
claim_count: 2
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
  - summary: Anti-social forces excluded
    text: 反社会的勢力(暴力団、暴力団員、暴力団員でなくなった時から5年を経過しない者、暴力団準構成員、暴力団関係企業、総会屋等、社会運動等標ぼうゴロまたは特殊知能暴力集団等、その他これらに準ずる者をいいます。) に該当しないこと
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Grafferアカウント保有者とは、アカウント登録フォーム上で当社の定める必要情報を登録し、当社の対象サービスの共有アカウントの利用につき、当社の承認を受けた者をいいます。
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Graffer
provenance_date: '2026-11-09'
provider_name: Graffer
provider_slug: graffer
slug: graffer-eligibility
source_date: '2026-11-09'
source_filename: graffer-eligibility.yml
source_heading: Eligibility
source_page: https://graffer.jp/legal/account-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Graffer\naid: graffer\nurl: https://graffer.jp/legal/account-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Anti-social forces excluded\n  text: 反社会的勢力(暴力団、暴力団員、暴力団員でなくなった時から5年を経過しない者、暴力団準構成員、暴力団関係企業、総会屋等、社会運動等標ぼうゴロまたは特殊知能暴力集団等、その他これらに準ずる者をいいます。) に該当しないこと\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Grafferアカウント保有者とは、アカウント登録フォーム上で当社の定める必要情報を登録し、当社の対象サービスの共有アカウントの利用につき、当社の承認を受けた者をいいます。\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/graffer/eligibility/graffer-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from Graffer's own page on 2026-11-09.
synthetic: false
tags:
- Company
- GovTech
- Government
- Artificial Intelligence
- Generative AI
- Digital Government
- Japan
- Software-as-a-Service
---
