---
api_specs:
- filename: hanyang-oai-pmh-api-openapi.yml
  format: yaml
  label: Hanyang University OAI PMH API
  slug: hanyang-oai-pmh-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hanyang/openapi/hanyang-oai-pmh-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 사업자회원은 상호명과 사업자등록번호
    type: business
  minimum_age:
    text: 회사는 청소년 보호법상 보호 대상인 회원, 만 20세 미만의 회원, 외국인 회원, 법인 및 단체 회원, 휴대폰 번호 회원 등에 대해 개별 서비스 이용을 제한할 수 있으며
    value: null
  restricted_uses:
  - summary: Product sales through the service
    text: 회원은 회사에서 공식적으로 인정한 경우를 제외하고는 서비스를 통한 상품 판매 영업을 할 수 없습니다.
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
name: Hanyang University
provenance_date: '2026-11-09'
provider_name: Hanyang University
provider_slug: hanyang
slug: hanyang-eligibility
source_date: '2026-11-09'
source_filename: hanyang-eligibility.yml
source_heading: Eligibility
source_page: https://api.hanyang.ac.kr/member/join_step01.page
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Hanyang University\naid: hanyang\nurl: https://api.hanyang.ac.kr/member/join_step01.page\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: 사업자회원은 상호명과 사업자등록번호\nrestricted_uses:\n- summary: Product sales through the service\n  text: 회원은 회사에서 공식적으로 인정한 경우를 제외하고는 서비스를 통한 상품 판매 영업을 할 수 없습니다.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: 회사는 청소년 보호법상 보호 대상인 회원, 만 20세 미만의 회원, 외국인 회원, 법인 및 단체 회원, 휴대폰 번호 회원 등에 대해 개별 서비스 이용을 제한할 수 있으며\n"
source_yaml_url: https://artifacts.apis.io/hanyang/eligibility/hanyang-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Hanyang University's own page on 2026-11-09.
synthetic: false
tags:
- Education
- Higher Education
- University
- South Korea
- Seoul
- Research Repository
- OAI-PMH
- OAuth
- OpenAPI
- Identity Federation
- Authentication
---
