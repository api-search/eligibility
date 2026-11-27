---
api_specs:
- filename: nthu-data-api.yaml
  format: yaml
  label: NTHU Data API
  slug: nthu-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nthu/openapi/_original/nthu-data-api.yaml
- filename: nthu-oauth-api-openapi.yml
  format: yaml
  label: National Tsing Hua University O Auth API
  slug: nthu-oauth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nthu/openapi/nthu-oauth-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: 外部系統帳號認證服務，可向單位主管簽核後提交計算機與通訊中心及相關單位審核，便可透過校務資訊系統進行身分認證。
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: National Tsing Hua University
provenance_date: '2026-11-10'
provider_name: National Tsing Hua University
provider_slug: nthu
slug: nthu-eligibility
source_date: '2026-11-10'
source_filename: nthu-eligibility.yml
source_heading: Eligibility
source_page: https://law.site.nthu.edu.tw/p/406-1326-197509,r6923.php
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: National Tsing Hua University\naid: nthu\nurl: https://law.site.nthu.edu.tw/p/406-1326-197509,r6923.php\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: 外部系統帳號認證服務，可向單位主管簽核後提交計算機與通訊中心及相關單位審核，便可透過校務資訊系統進行身分認證。\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/nthu/eligibility/nthu-eligibility.yml
stated_fields:
- verification
summary_line: 1 quoted statement, read from National Tsing Hua University's own page on 2026-11-10.
synthetic: false
tags:
- Education
- Higher Education
- University
- Taiwan
- Public Research University
- Identity
- Authentication
- Open Data
- Campus
- Course Catalog
- Research Repository
- Library
- Identity Federation
---
