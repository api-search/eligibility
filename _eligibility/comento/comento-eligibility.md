---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: 코멘토는 관계법령에서 규정하는 미성년자일 경우에 이용계약 신청의 승낙을 보류할 수 있습니다.
    value: null
  restricted_uses:
  - summary: Confidential company information not queryable
    text: 회사의 영업비밀 및 기술비밀 등 회사의 기밀에 관련된 내용.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: 코멘토는 제6조에 따른 “이용자”의 이용신청에 대하여 신용정보의 이용 및 보호에 관한 법률이 정하는 특별한 사정이 없는 한 접수 순서대로 이용 신청을 승낙합니다.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Comento
provenance_date: '2026-11-09'
provider_name: Comento
provider_slug: comento
slug: comento-eligibility
source_date: '2026-11-09'
source_filename: comento-eligibility.yml
source_heading: Eligibility
source_page: https://comento.kr/agreement
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Comento\naid: comento\nurl: https://comento.kr/agreement\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Confidential company information not queryable\n  text: 회사의 영업비밀 및 기술비밀 등 회사의 기밀에 관련된 내용.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: 코멘토는 제6조에 따른 “이용자”의 이용신청에 대하여 신용정보의 이용 및 보호에 관한 법률이 정하는 특별한 사정이 없는 한 접수 순서대로 이용 신청을 승낙합니다.\nminimum_age:\n  value: null\n  text: 코멘토는 관계법령에서 규정하는 미성년자일 경우에 이용계약 신청의 승낙을 보류할 수 있습니다.\n"
source_yaml_url: https://artifacts.apis.io/comento/eligibility/comento-eligibility.yml
stated_fields:
- restricted_uses
- verification
- minimum_age
summary_line: 3 quoted statements, read from Comento's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Careers
- Mentoring
- Recruiting
- Education
- Job
- Community
- South Korea
---
