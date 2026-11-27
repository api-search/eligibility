---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: '회원 : 본 약관에 동의하고 서비스 이용에 필요한 사용자 아이디와 사용자 비밀번호를 부여받아 회사가 운영하는 사이트에서 서비스를 이용하는 개인을 말합니다.'
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Illegal or disruptive activity
    text: 회원은 서비스를 이용함에 있어 공공질서 또는 미풍양속을 해치는 행위, 또는 다음 각호에 해당하는 행위를 해서는 안됩니다.
  verification:
    approval_required: true
    kyb: null
    kyc: true
    text: 회사는 이를 회사가 정한 실명확인절차를 거쳐 회원가입을 승낙하는 것을 원칙으로 합니다.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Aoruibio
provenance_date: '2026-11-09'
provider_name: Aoruibio
provider_slug: aoruibio
slug: aoruibio-eligibility
source_date: '2026-11-09'
source_filename: aoruibio-eligibility.yml
source_heading: Eligibility
source_page: https://aulbio.com/etc/agreement.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Aoruibio\naid: aoruibio\nurl: https://aulbio.com/etc/agreement.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: '회원 : 본 약관에 동의하고 서비스 이용에 필요한 사용자 아이디와 사용자 비밀번호를 부여받아 회사가 운영하는 사이트에서 서비스를 이용하는 개인을 말합니다.'\nrestricted_uses:\n- summary: Illegal or disruptive activity\n  text: 회원은 서비스를 이용함에 있어 공공질서 또는 미풍양속을 해치는 행위, 또는 다음 각호에 해당하는 행위를 해서는 안됩니다.\nverification:\n  kyc: true\n  kyb: null\n  approval_required: true\n  text: 회사는 이를 회사가 정한 실명확인절차를 거쳐 회원가입을 승낙하는 것을 원칙으로 합니다.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/aoruibio/eligibility/aoruibio-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from Aoruibio's own page on 2026-11-09.
synthetic: false
tags:
- Biotechnology
- Healthcare
- Drug Delivery
- Platform
- South Korea
---
