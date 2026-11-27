---
api_specs:
- filename: datarize-openapi-generated.yml
  format: yaml
  label: Datarize API
  slug: datarize-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/datarize/openapi/_ae-authored/datarize-openapi-generated.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: 회원이 대한민국에 사업장(사업장이 없는 경우에는 주소 또는 거소를 말합니다)을 둔 경우, 회사와 회원은 본 서비스가 국내 용역 거래에 해당함에 상호 동의하며
  entity_types:
  - text: 회원이 법인·단체인 경우 그 구성원을 포함합니다
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Illegal spam or phishing messages
    text: 회원이 전송한 메시지가 불법스팸메시지·피싱메시지로 확인된 경우
  verification:
    approval_required: true
    kyb: null
    kyc: true
    text: 회사는 전문기관을 통한 실명 확인 또는 본인인증을 요청할 수 있습니다. 다만, 메시지 서비스를 이용하려는 회원에 대하여는 관련 법령에 따라 본인확인을 합니다.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Datarize
provenance_date: '2026-11-09'
provider_name: Datarize
provider_slug: datarize
slug: datarize-eligibility
source_date: '2026-11-09'
source_filename: datarize-eligibility.yml
source_heading: Eligibility
source_page: https://policy.datarize.ai/ko/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Datarize\naid: datarize\nurl: https://policy.datarize.ai/ko/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: 회원이 대한민국에 사업장(사업장이 없는 경우에는 주소 또는 거소를 말합니다)을 둔 경우, 회사와 회원은 본 서비스가 국내 용역 거래에 해당함에 상호 동의하며\nentity_types:\n- type: business\n  text: 회원이 법인·단체인 경우 그 구성원을 포함합니다\nrestricted_uses:\n- summary: Illegal spam or phishing messages\n  text: 회원이 전송한 메시지가 불법스팸메시지·피싱메시지로 확인된 경우\nverification:\n  kyc: true\n  kyb: null\n  approval_required: true\n  text: 회사는 전문기관을 통한 실명 확인 또는 본인인증을 요청할 수 있습니다. 다만, 메시지 서비스를 이용하려는 회원에 대하여는 관련 법령에 따라 본인확인을 합니다.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/datarize/eligibility/datarize-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from Datarize's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Data Integration
- Analytics
- API Platform
- Enterprise
---
