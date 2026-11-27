---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: なお、本サービスは日本国内の個人のご利用を想定しております。
  entity_types:
  - text: 本サービスは日本国内の個人のご利用を想定しております。
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Investment solicitation or advice
    text: 本サービスは、株式取引と口座開設に伴う注文サポート機能、資産管理、株式情報サーチ機能や取引履歴参照等を提供することを目的としたものであり、投資への勧誘及び助言をすることを目的としたものではありません。
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
name: Woodstock
provenance_date: '2026-11-10'
provider_name: Woodstock
provider_slug: woodstock
slug: woodstock-eligibility
source_date: '2026-11-10'
source_filename: woodstock-eligibility.yml
source_heading: Eligibility
source_page: https://woodstock.co/ja/legal/term-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Woodstock\naid: woodstock\nurl: https://woodstock.co/ja/legal/term-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: なお、本サービスは日本国内の個人のご利用を想定しております。\nentity_types:\n- type: individual\n  text: 本サービスは日本国内の個人のご利用を想定しております。\nrestricted_uses:\n- summary: Investment solicitation or advice\n  text: 本サービスは、株式取引と口座開設に伴う注文サポート機能、資産管理、株式情報サーチ機能や取引履歴参照等を提供することを目的としたものであり、投資への勧誘及び助言をすることを目的としたものではありません。\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/woodstock/eligibility/woodstock-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Woodstock's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Investing
- Stock Trading
- Brokerage
- Fintech
- Japan
- MCP
- AI Agents
- Financial Services
---
