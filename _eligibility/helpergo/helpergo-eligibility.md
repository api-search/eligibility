---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - HK
    - SG
    text: 香港 | 新加坡
  entity_types:
  - text: 在本協議期限內，“HelperGo”軟件為個人使用（或使用人，包括公司或其他組織）。
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Personal use only, no other purpose
    text: 不得利用“HelperGo”軟件來用於任何其他目的或任何未經本公司事先書面許可，任何商業行為或其他行為。
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: 用戶必須向本公司提供準確、真實的個人相關資料，且需要通過認證方能開始使用軟件。
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: HelperGo
provenance_date: '2026-11-09'
provider_name: HelperGo
provider_slug: helpergo
slug: helpergo-eligibility
source_date: '2026-11-09'
source_filename: helpergo-eligibility.yml
source_heading: Eligibility
source_page: https://helpergo.co/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: HelperGo\naid: helpergo\nurl: https://helpergo.co/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - HK\n  - SG\n  excluded: []\n  text: 香港 | 新加坡\nentity_types:\n- type: individual\n  text: 在本協議期限內，“HelperGo”軟件為個人使用（或使用人，包括公司或其他組織）。\nrestricted_uses:\n- summary: Personal use only, no other purpose\n  text: 不得利用“HelperGo”軟件來用於任何其他目的或任何未經本公司事先書面許可，任何商業行為或其他行為。\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: 用戶必須向本公司提供準確、真實的個人相關資料，且需要通過認證方能開始使用軟件。\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/helpergo/eligibility/helpergo-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from HelperGo's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Home Services
- Marketplace
- On-Demand
- Consumer
- Hong Kong
- Cleaning
- Childcare
---
