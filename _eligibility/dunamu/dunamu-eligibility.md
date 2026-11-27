---
api_specs:
- filename: dunamu-exchange-api-openapi.yml
  format: yaml
  label: Dunamu Exchange API
  slug: dunamu-exchange-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dunamu/openapi/dunamu-exchange-api-openapi.yml
- filename: dunamu-quotation-api-openapi.yml
  format: yaml
  label: Dunamu Quotation API
  slug: dunamu-quotation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dunamu/openapi/dunamu-quotation-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 회원은 본인 명의로 1개의 계정만을 사용할 수 있고
    type: individual
  - text: 법인회원은 이에 더하여 '업비트 법인회원 부속약관'을 준수하여야 하며
    type: business
  minimum_age:
    text: 가입 신청자가 비거주자, 외국법인 혹은 미성년자인 경우
    value: null
  restricted_uses:
  - summary: Deposits to trade on behalf of others
    text: 구매대행 등 타인을 대신하여 디지털 자산을 거래하기 위하여 입금한 경우
  - summary: Sanctioned-country access
    text: 회원의 계정으로 서비스 이용을 시도하는 IP 주소가 제재국가의 IP 주소인 경우
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: 신규 가입 시 고객확인절차가 완료되고 CARF이행규정에 따른 본인확인서가 정상적으로 제출 완료된 시점부터 서비스를 이용할 수 있습니다.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Dunamu
provenance_date: '2026-11-09'
provider_name: Dunamu
provider_slug: dunamu
slug: dunamu-eligibility
source_date: '2026-11-09'
source_filename: dunamu-eligibility.yml
source_heading: Eligibility
source_page: https://www.upbit.com/terms_of_service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Dunamu\naid: dunamu\nurl: https://www.upbit.com/terms_of_service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: 회원은 본인 명의로 1개의 계정만을 사용할 수 있고\n- type: business\n  text: 법인회원은 이에 더하여 '업비트 법인회원 부속약관'을 준수하여야 하며\nrestricted_uses:\n- summary: Deposits to trade on behalf of others\n  text: 구매대행 등 타인을 대신하여 디지털 자산을 거래하기 위하여 입금한 경우\n- summary: Sanctioned-country access\n  text: 회원의 계정으로 서비스 이용을 시도하는 IP 주소가 제재국가의 IP 주소인 경우\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: 신규 가입 시 고객확인절차가 완료되고 CARF이행규정에 따른 본인확인서가 정상적으로\
  \ 제출 완료된 시점부터 서비스를 이용할 수 있습니다.\nminimum_age:\n  value: null\n  text: 가입 신청자가 비거주자, 외국법인 혹은 미성년자인 경우\n"
source_yaml_url: https://artifacts.apis.io/dunamu/eligibility/dunamu-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Dunamu's own page on 2026-11-09.
synthetic: false
tags:
- Fintech
- Cryptocurrency
- Digital Assets
- Exchange
- Securities
- Trading
- Blockchain
- South Korea
- Company
---
