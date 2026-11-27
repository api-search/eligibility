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
  - summary: Solicitation of high-priced courses or off-platform payments
    text: 高額な商材やコンサルティングへの勧誘、当サービス外の決済手段への誘導
  verification:
    approval_required: false
    kyb: null
    kyc: null
    text: 出品は事前の審査なしに公開されます。
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Chiemem
provenance_date: '2026-11-09'
provider_name: Chiemem
provider_slug: chiemem-com
slug: chiemem-com-eligibility
source_date: '2026-11-09'
source_filename: chiemem-com-eligibility.yml
source_heading: Eligibility
source_page: https://chiemem.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Chiemem\naid: chiemem-com\nurl: https://chiemem.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Solicitation of high-priced courses or off-platform payments\n  text: 高額な商材やコンサルティングへの勧誘、当サービス外の決済手段への誘導\nverification:\n  kyc: null\n  kyb: null\n  approval_required: false\n  text: 出品は事前の審査なしに公開されます。\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/chiemem-com/eligibility/chiemem-com-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from Chiemem's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Marketplace
- Prompts
- Artificial Intelligence
- Generative AI
- Digital Content
- Japan
- MCP
---
