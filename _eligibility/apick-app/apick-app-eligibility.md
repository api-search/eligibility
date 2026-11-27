---
api_specs:
- filename: apick-app-openapi-generated.yml
  format: yaml
  label: apick-app API
  slug: apick-app-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apick-app/openapi/_ae-authored/apick-app-openapi-generated.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: '''회사''가 제공하는 ''서비스''에 가입하여 계약을 체결한 개인 및 기업, 단체를 말합니다.'
    type: individual
  - text: '''회사''가 제공하는 ''서비스''에 가입하여 계약을 체결한 개인 및 기업, 단체를 말합니다.'
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: 사전 동의 없는 영리 목적 이용
    text: 회사의 사전 동의 없이 영리 추구 목적으로 서비스를 이용하고자 하는 경우
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: 회원가입은 가입 요청 후 이메일 인증까지 완료한 경우 회원 등록이 완료(회원가입이 완료)되며 서비스를 이용할 수 있습니다.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: apick-app
provenance_date: '2026-11-09'
provider_name: apick-app
provider_slug: apick-app
slug: apick-app-eligibility
source_date: '2026-11-09'
source_filename: apick-app-eligibility.yml
source_heading: Eligibility
source_page: https://apick.app/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: apick-app\naid: apick-app\nurl: https://apick.app/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: '''회사''가 제공하는 ''서비스''에 가입하여 계약을 체결한 개인 및 기업, 단체를 말합니다.'\n- type: business\n  text: '''회사''가 제공하는 ''서비스''에 가입하여 계약을 체결한 개인 및 기업, 단체를 말합니다.'\nrestricted_uses:\n- summary: 사전 동의 없는 영리 목적 이용\n  text: 회사의 사전 동의 없이 영리 추구 목적으로 서비스를 이용하고자 하는 경우\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: 회원가입은 가입 요청 후 이메일 인증까지 완료한 경우 회원 등록이 완료(회원가입이 완료)되며 서비스를 이용할 수 있습니다.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/apick-app/eligibility/apick-app-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from apick-app's own page on 2026-11-09.
synthetic: false
tags:
- Korean
- Platform
- Data
- Services
---
