---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: ‘회사’는 출생 연도에 대한 정보를 수집하지 않고 있으나, 부모와 자녀 연동 기능을 통해 만 14세 미만 ‘회원’이 부모의 동의를 받도록 조치하고 있습니다.
    value: '14'
  verification:
    approval_required: false
    kyb: null
    kyc: null
    text: ‘회사’는 가입 신청자의 신청에 대하여 서비스 이용을 승낙하는 것을 원칙으로 합니다.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Classtinginc
provenance_date: '2026-11-09'
provider_name: Classtinginc
provider_slug: classtinginc
slug: classtinginc-eligibility
source_date: '2026-11-09'
source_filename: classtinginc-eligibility.yml
source_heading: Eligibility
source_page: https://policies.classting.com/ko/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Classtinginc\naid: classtinginc\nurl: https://policies.classting.com/ko/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: false\n  text: ‘회사’는 가입 신청자의 신청에 대하여 서비스 이용을 승낙하는 것을 원칙으로 합니다.\nminimum_age:\n  value: '14'\n  text: ‘회사’는 출생 연도에 대한 정보를 수집하지 않고 있으나, 부모와 자녀 연동 기능을 통해 만 14세 미만 ‘회원’이 부모의 동의를 받도록 조치하고 있습니다.\n"
source_yaml_url: https://artifacts.apis.io/classtinginc/eligibility/classtinginc-eligibility.yml
stated_fields:
- verification
- minimum_age
summary_line: 2 quoted statements, read from Classtinginc's own page on 2026-11-09.
synthetic: false
tags:
- Education
- Artificial Intelligence
- K-12
- Personalized Learning
- EdTech
---
