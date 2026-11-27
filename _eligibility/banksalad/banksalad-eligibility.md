---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: 만 14세 미만의 아동, 관련 법령이나 본 약관을 위반하여 가입하려는 자는 회원가입 및 서비스 이용이 제한됩니다.
    value: '14'
  restricted_uses:
  - summary: No use under another's name
    text: 이용자는 어떠한 경우에도 타인의 명의를 사용하여 회원으로 가입하여서는 안됩니다.
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
name: Banksalad
provenance_date: '2026-11-09'
provider_name: Banksalad
provider_slug: banksalad
slug: banksalad-eligibility
source_date: '2026-11-09'
source_filename: banksalad-eligibility.yml
source_heading: Eligibility
source_page: https://policies.banksalad.com/%EB%B1%85%ED%81%AC%EC%83%90%EB%9F%AC%EB%93%9C/%EC%84%9C%EB%B9%84%EC%8A%A4-%EC%9D%B4%EC%9A%A9-%EC%95%BD%EA%B4%80/v2/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Banksalad\naid: banksalad\nurl: https://policies.banksalad.com/%EB%B1%85%ED%81%AC%EC%83%90%EB%9F%AC%EB%93%9C/%EC%84%9C%EB%B9%84%EC%8A%A4-%EC%9D%B4%EC%9A%A9-%EC%95%BD%EA%B4%80/v2/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: No use under another's name\n  text: 이용자는 어떠한 경우에도 타인의 명의를 사용하여 회원으로 가입하여서는 안됩니다.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '14'\n  text: 만 14세 미만의 아동, 관련 법령이나 본 약관을 위반하여 가입하려는 자는 회원가입 및 서비스 이용이 제한됩니다.\n"
source_yaml_url: https://artifacts.apis.io/banksalad/eligibility/banksalad-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Banksalad's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- South Korea
- Financial Services
- Health Tech
---
