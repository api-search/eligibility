---
claim_count: 7
description: ''
doc:
  countries:
    excluded: []
    served:
    - JP
    text: 本サービスの利用者は、18歳以上であり、日本国内の居住者又は法人である必要があります。
  entity_types:
  - text: 本サービスの利用者は、18歳以上であり、日本国内の居住者又は法人である必要があります。
    type: individual
  - text: 利用者が本サービスを事業のために利用する場合は
    type: business
  minimum_age:
    text: 本サービスの利用者は、18歳以上であり、日本国内の居住者又は法人である必要があります。
    value: '18'
  restricted_uses:
  - summary: High-stakes decisions without professional review
    text: 唯一の情報源若しくは証拠、又は専門家の助言の代わりとして、本サービスを使用する行為
  - summary: Trade-restricted end uses
    text: 本サービスは、取引に関する適用法令において禁止されている最終用途のために使用してはならず
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: 当社は、登録申込者が以下の各号のいずれかに該当する場合は、本サービスの利用登録の申込みを承諾しないことがあります
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Preferred Networks
provenance_date: '2026-11-10'
provider_name: Preferred Networks
provider_slug: preferred-networks
slug: preferred-networks-eligibility
source_date: '2026-11-10'
source_filename: preferred-networks-eligibility.yml
source_heading: Eligibility
source_page: https://plamo.preferredai.jp/info/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Preferred Networks\naid: preferred-networks\nurl: https://plamo.preferredai.jp/info/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - JP\n  excluded: []\n  text: 本サービスの利用者は、18歳以上であり、日本国内の居住者又は法人である必要があります。\nentity_types:\n- type: individual\n  text: 本サービスの利用者は、18歳以上であり、日本国内の居住者又は法人である必要があります。\n- type: business\n  text: 利用者が本サービスを事業のために利用する場合は\nrestricted_uses:\n- summary: High-stakes decisions without professional review\n  text: 唯一の情報源若しくは証拠、又は専門家の助言の代わりとして、本サービスを使用する行為\n- summary: Trade-restricted end uses\n  text: 本サービスは、取引に関する適用法令において禁止されている最終用途のために使用してはならず\nverification:\n  kyc: null\n  kyb: null\n\
  \  approval_required: true\n  text: 当社は、登録申込者が以下の各号のいずれかに該当する場合は、本サービスの利用登録の申込みを承諾しないことがあります\nminimum_age:\n  value: '18'\n  text: 本サービスの利用者は、18歳以上であり、日本国内の居住者又は法人である必要があります。\n"
source_yaml_url: https://artifacts.apis.io/preferred-networks/eligibility/preferred-networks-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 7 quoted statements, read from Preferred Networks's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Machine Learning
- LLM
- Generative AI
- Inference
- Foundation Models
- Japan
- Semiconductors
- Supercomputing
- Translation
- MCP
---
