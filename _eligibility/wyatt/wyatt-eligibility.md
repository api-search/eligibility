---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: 만 14세 미만의 경우
    value: '14'
  restricted_uses:
  - summary: Minor purchases of restricted goods
    text: 미성년자가 담배, 주류 등 청소년보호법에서 금지하는 재화 및 용역을 구매하는 경우
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
name: Wyatt
provenance_date: '2026-11-10'
provider_name: Wyatt
provider_slug: wyatt
slug: wyatt-eligibility
source_date: '2026-11-10'
source_filename: wyatt-eligibility.yml
source_heading: Eligibility
source_page: https://drforhair.co.kr/member/agreement.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Wyatt\naid: wyatt\nurl: https://drforhair.co.kr/member/agreement.html\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Minor purchases of restricted goods\n  text: 미성년자가 담배, 주류 등 청소년보호법에서 금지하는 재화 및 용역을 구매하는 경우\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '14'\n  text: 만 14세 미만의 경우\n"
source_yaml_url: https://artifacts.apis.io/wyatt/eligibility/wyatt-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Wyatt's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Beauty
- Personal Care
- Hair Care
- Consumer Products
- E-Commerce
- Retail
- Agentic Commerce
- MCP
- South Korea
---
