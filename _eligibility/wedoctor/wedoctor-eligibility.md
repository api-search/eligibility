---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - CN
    text: 由微医在中国境内设立、接入微医平台并通过微医平台提供互联网诊疗服务的互联网医院
  entity_types:
  - text: 用户：指微医生产品、服务的使用人，即医生
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No business outside authorized scope
    text: 不利用互联网医院、微医平台或微医相关的企业品牌开展非本协议授权或约定范围内的业务
  verification:
    approval_required: true
    kyb: null
    kyc: true
    text: 还需进行实名认证并通过所属互联网医院审查
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: WeDoctor
provenance_date: '2026-11-10'
provider_name: WeDoctor
provider_slug: wedoctor
slug: wedoctor-eligibility
source_date: '2026-11-10'
source_filename: wedoctor-eligibility.yml
source_heading: Eligibility
source_page: https://wedoctor.com/agreement/doctor
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: WeDoctor\naid: wedoctor\nurl: https://wedoctor.com/agreement/doctor\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - CN\n  excluded: []\n  text: 由微医在中国境内设立、接入微医平台并通过微医平台提供互联网诊疗服务的互联网医院\nentity_types:\n- type: individual\n  text: 用户：指微医生产品、服务的使用人，即医生\nrestricted_uses:\n- summary: No business outside authorized scope\n  text: 不利用互联网医院、微医平台或微医相关的企业品牌开展非本协议授权或约定范围内的业务\nverification:\n  kyc: true\n  kyb: null\n  approval_required: true\n  text: 还需进行实名认证并通过所属互联网医院审查\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/wedoctor/eligibility/wedoctor-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from WeDoctor's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- Digital Health
- Telehealth
- Internet Hospital
- Appointment Booking
- Electronic Prescription
- Health Insurance
- China
---
