---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 法人様の場合、お支払いには請求書払い（銀行振込）又は代理店払いをご利用いただけます。
    type: business
  - text: 個人/個人事業主様の場合は、前払い後の商品発送となります。
    type: individual
  minimum_age:
    text: null
    value: null
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
name: AgroDesign Studios
provenance_date: '2026-11-09'
provider_name: AgroDesign Studios
provider_slug: agrodesignstudio
slug: agrodesignstudio-eligibility
source_date: '2026-11-09'
source_filename: agrodesignstudio-eligibility.yml
source_heading: Eligibility
source_page: https://www.agrobox.jp/tokusyohou
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AgroDesign Studios\naid: agrodesignstudio\nurl: https://www.agrobox.jp/tokusyohou\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: 法人様の場合、お支払いには請求書払い（銀行振込）又は代理店払いをご利用いただけます。\n- type: individual\n  text: 個人/個人事業主様の場合は、前払い後の商品発送となります。\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/agrodesignstudio/eligibility/agrodesignstudio-eligibility.yml
stated_fields:
- entity_types
summary_line: 2 quoted statements, read from AgroDesign Studios's own page on 2026-11-09.
synthetic: false
tags:
- Agriculture
- AgTech
- Biotechnology
- Life Sciences
- Structural Biology
- Drug Discovery
- Crop Protection
- Contract Research
- Laboratory Automation
- Japan
- MCP
- Company
---
