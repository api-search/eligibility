---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 만 14세 미만의 이용자는 회사 웹사이트에서 전자적 표시 형태로 제공되는 개인정보처리방침을 충분히 숙지한 후, 반드시 보호자[법정대리인]의 동의를 얻어 회원 가입을 신청 하여야 하는 등
    type: individual
  minimum_age:
    text: 만 14세 미만의 이용자는 회사 웹사이트에서 전자적 표시 형태로 제공되는 개인정보처리방침을 충분히 숙지한 후, 반드시 보호자[법정대리인]의 동의를 얻어 회원 가입을 신청 하여야 하는 등
    value: '14'
  restricted_uses:
  - summary: Commercial sales via the service
    text: 회원이 회사에서 제공하는 서비스를 이용하여 상품 또는 용역을 판매하는 영업활동 등의 상행위를 하는 경우
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: 회사는 본 조 제1항에 따른 이용자의 신청에 대하여 회원 가입을 승낙함을 원칙으로 합니다.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Dankkumi
provenance_date: '2026-11-09'
provider_name: Dankkumi
provider_slug: dankkumi
slug: dankkumi-eligibility
source_date: '2026-11-09'
source_filename: dankkumi-eligibility.yml
source_heading: Eligibility
source_page: https://www.dankkumi.com/Terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Dankkumi\naid: dankkumi\nurl: https://www.dankkumi.com/Terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: 만 14세 미만의 이용자는 회사 웹사이트에서 전자적 표시 형태로 제공되는 개인정보처리방침을 충분히 숙지한 후, 반드시 보호자[법정대리인]의 동의를 얻어 회원 가입을 신청 하여야 하는 등\nrestricted_uses:\n- summary: Commercial sales via the service\n  text: 회원이 회사에서 제공하는 서비스를 이용하여 상품 또는 용역을 판매하는 영업활동 등의 상행위를 하는 경우\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: 회사는 본 조 제1항에 따른 이용자의 신청에 대하여 회원 가입을 승낙함을 원칙으로 합니다.\nminimum_age:\n  value: '14'\n  text: 만 14세 미만의 이용자는 회사 웹사이트에서 전자적\
  \ 표시 형태로 제공되는 개인정보처리방침을 충분히 숙지한 후, 반드시 보호자[법정대리인]의 동의를 얻어 회원 가입을 신청 하여야 하는 등\n"
source_yaml_url: https://artifacts.apis.io/dankkumi/eligibility/dankkumi-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Dankkumi's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Education
- Children
- Korean
- History
---
