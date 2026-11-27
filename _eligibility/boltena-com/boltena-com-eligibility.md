---
api_specs:
- filename: boltena-com-default-api-openapi.yml
  format: yaml
  label: 볼테나 기본 API
  slug: boltena-com-default-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/boltena-com/openapi/boltena-com-default-api-openapi.yml
- filename: boltena-com-eqp-api-openapi.yml
  format: yaml
  label: 볼테나 EQP 모듈 필요 API
  slug: boltena-com-eqp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/boltena-com/openapi/boltena-com-eqp-api-openapi.yml
- filename: boltena-com-hr-api-openapi.yml
  format: yaml
  label: 볼테나 HR 모듈 필요 API
  slug: boltena-com-hr-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/boltena-com/openapi/boltena-com-hr-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 가입 시 기재된 회사(사업자, 이하 "고객사")입니다.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Misuse of company identity or repeated fraudulent signups
    text: 타인의 회사 명의 도용, 부정한 반복 가입, 서비스의 정상 운영을 방해하는 행위가 확인되면 사전 통지 없이 이용을 제한하거나 해지할 수 있습니다.
  verification:
    approval_required: null
    kyb: true
    kyc: null
    text: 서비스가 제공하는 사업자등록번호 확인은 국세청에 등록된 번호인지와 그 상태(계속사업자· 휴업·폐업)를 확인하는 절차입니다.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: 볼테나
provenance_date: '2026-11-09'
provider_name: 볼테나
provider_slug: boltena-com
slug: boltena-com-eligibility
source_date: '2026-11-09'
source_filename: boltena-com-eligibility.yml
source_heading: Eligibility
source_page: https://boltena.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: 볼테나\naid: boltena-com\nurl: https://boltena.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: 가입 시 기재된 회사(사업자, 이하 \"고객사\")입니다.\nrestricted_uses:\n- summary: Misuse of company identity or repeated fraudulent signups\n  text: 타인의 회사 명의 도용, 부정한 반복 가입, 서비스의 정상 운영을 방해하는 행위가 확인되면 사전 통지 없이 이용을 제한하거나 해지할 수 있습니다.\nverification:\n  kyc: null\n  kyb: true\n  approval_required: null\n  text: 서비스가 제공하는 사업자등록번호 확인은 국세청에 등록된 번호인지와 그 상태(계속사업자· 휴업·폐업)를 확인하는 절차입니다.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/boltena-com/eligibility/boltena-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from 볼테나's own page on 2026-11-09.
synthetic: false
tags:
- ERP
- Human Resources
- MES
- Business Intelligence
---
