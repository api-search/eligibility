---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 指具有完全民事行为能力的本平台使用者（求职者和招聘者）
    type: individual
  - text: 如您为招聘者，您需是符合中华人民共和国法律、行政法规、部门规章等规范性文件要求，合法设立并存续的企业、机关、社团、事业单位和其他组织
    type: business
  minimum_age:
    text: 在注册之日必须年满16周岁以上。
    value: '16'
  restricted_uses:
  - summary: Uses beyond job search/recruiting
    text: 禁止用户利用本平台的产品/服务从事超出前述目的、违反法律法规、损害其他用户或51Job合法权益的行为。
  verification:
    approval_required: true
    kyb: true
    kyc: null
    text: 用户应按照51Job要求，提供招聘方相关资料并通过51Job审查后，方可发布招聘信息、进行招聘活动。
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: 51job
provenance_date: '2026-11-09'
provider_name: 51job
provider_slug: 51job
slug: 51job-eligibility
source_date: '2026-11-09'
source_filename: 51job-eligibility.yml
source_heading: Eligibility
source_page: https://we.51job.com/service?type=1#topIndex
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: 51job\naid: 51job\nurl: https://we.51job.com/service?type=1#topIndex\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: 指具有完全民事行为能力的本平台使用者（求职者和招聘者）\n- type: business\n  text: 如您为招聘者，您需是符合中华人民共和国法律、行政法规、部门规章等规范性文件要求，合法设立并存续的企业、机关、社团、事业单位和其他组织\nrestricted_uses:\n- summary: Uses beyond job search/recruiting\n  text: 禁止用户利用本平台的产品/服务从事超出前述目的、违反法律法规、损害其他用户或51Job合法权益的行为。\nverification:\n  kyc: null\n  kyb: true\n  approval_required: true\n  text: 用户应按照51Job要求，提供招聘方相关资料并通过51Job审查后，方可发布招聘信息、进行招聘活动。\nminimum_age:\n  value: '16'\n  text: 在注册之日必须年满16周岁以上。\n"
source_yaml_url: https://artifacts.apis.io/51job/eligibility/51job-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from 51job's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Enterprise
- Recruiting
- Human Resources
- Job Search
- Hiring
- China
- Staffing
---
