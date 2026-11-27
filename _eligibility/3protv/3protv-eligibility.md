---
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
    text: '"회사"는 제6조의 "회원" 가입 신청에 대하여 승낙함을 원칙으로 합니다.'
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: 3ProTV
provenance_date: '2026-11-09'
provider_name: 3ProTV
provider_slug: 3protv
slug: 3protv-eligibility
source_date: '2026-11-09'
source_filename: 3protv-eligibility.yml
source_heading: Eligibility
source_page: https://apps.3protv.com/policy/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: 3ProTV\naid: 3protv\nurl: https://apps.3protv.com/policy/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: '\"회사\"는 제6조의 \"회원\" 가입 신청에 대하여 승낙함을 원칙으로 합니다.'\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/3protv/eligibility/3protv-eligibility.yml
stated_fields:
- verification
summary_line: 1 quoted statement, read from 3ProTV's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Media
- Financial Media
- Video
- Streaming
- Subscription
- Education
- South Korea
- Content
---
