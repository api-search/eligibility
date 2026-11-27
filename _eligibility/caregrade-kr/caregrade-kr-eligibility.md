---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 기관명, 사업자등록번호(또는 고유번호), 담당자 이름·이메일·연락처를 넣어 신청합니다.
    type: business
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
name: 케어그레이드
provenance_date: '2026-11-09'
provider_name: 케어그레이드
provider_slug: caregrade-kr
slug: caregrade-kr-eligibility
source_date: '2026-11-09'
source_filename: caregrade-kr-eligibility.yml
source_heading: Eligibility
source_page: https://caregrade.kr/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: 케어그레이드\naid: caregrade-kr\nurl: https://caregrade.kr/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: 기관명, 사업자등록번호(또는 고유번호), 담당자 이름·이메일·연락처를 넣어 신청합니다.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/caregrade-kr/eligibility/caregrade-kr-eligibility.yml
stated_fields:
- entity_types
summary_line: 1 quoted statement, read from 케어그레이드's own page on 2026-11-09.
synthetic: false
tags:
- Healthcare
- Data
- South Korea
- Long-Term Care
- Public
---
