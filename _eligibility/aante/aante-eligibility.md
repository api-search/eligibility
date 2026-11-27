---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - CN
    text: 本网站所刊载的产品和服务仅面向中国大陆地区用户。
  entity_types:
  - text: 用户应为具备完全民事行为能力的自然人
    type: individual
  - text: 依法成立、存续的法人或其他组织。
    type: business
  minimum_age:
    text: 如果用户是 18 周岁以下的自然人，则应当在监护人的监护参与下使用本网站。
    value: '18'
  restricted_uses:
  - summary: Prohibited conduct on the site
    text: 用户在使用本网站服务时禁止下述各项行为
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: 注册资料应当真实、准确、完整、合法、有效。
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Aante
provenance_date: '2026-11-09'
provider_name: Aante
provider_slug: aante
slug: aante-eligibility
source_date: '2026-11-09'
source_filename: aante-eligibility.yml
source_heading: Eligibility
source_page: https://ant-fa.com/notice/notice-detail/44/?id=44
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Aante\naid: aante\nurl: https://ant-fa.com/notice/notice-detail/44/?id=44\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - CN\n  excluded: []\n  text: 本网站所刊载的产品和服务仅面向中国大陆地区用户。\nentity_types:\n- type: individual\n  text: 用户应为具备完全民事行为能力的自然人\n- type: business\n  text: 依法成立、存续的法人或其他组织。\nrestricted_uses:\n- summary: Prohibited conduct on the site\n  text: 用户在使用本网站服务时禁止下述各项行为\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: 注册资料应当真实、准确、完整、合法、有效。\nminimum_age:\n  value: '18'\n  text: 如果用户是 18 周岁以下的自然人，则应当在监护人的监护参与下使用本网站。\n"
source_yaml_url: https://artifacts.apis.io/aante/eligibility/aante-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Aante's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Industrial Automation
- Factory Automation
- Manufacturing
- Distribution
- E-Commerce
- Procurement
- Industrial Components
- China
---
