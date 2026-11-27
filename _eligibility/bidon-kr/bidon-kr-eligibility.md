---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: 만 14세 미만은 가입할 수 없습니다.
    value: '14'
  verification:
    approval_required: null
    kyb: true
    kyc: null
    text: 회사는 회원의 회사 정보(사업자등록증 등)를 확인하여 "인증 완료" 표시를 부여할 수 있습니다.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: 비드온 BIDON
provenance_date: '2026-11-09'
provider_name: 비드온 BIDON
provider_slug: bidon-kr
slug: bidon-kr-eligibility
source_date: '2026-11-09'
source_filename: bidon-kr-eligibility.yml
source_heading: Eligibility
source_page: https://bidon.kr/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: 비드온 BIDON\naid: bidon-kr\nurl: https://bidon.kr/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: true\n  approval_required: null\n  text: 회사는 회원의 회사 정보(사업자등록증 등)를 확인하여 \"인증 완료\" 표시를 부여할 수 있습니다.\nminimum_age:\n  value: '14'\n  text: 만 14세 미만은 가입할 수 없습니다.\n"
source_yaml_url: https://artifacts.apis.io/bidon-kr/eligibility/bidon-kr-eligibility.yml
stated_fields:
- verification
- minimum_age
summary_line: 2 quoted statements, read from 비드온 BIDON's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Procurement
- Marketplace
- Free
---
