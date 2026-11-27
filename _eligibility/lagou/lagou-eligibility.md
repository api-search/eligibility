---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 具备完全民事行为能力的自然人（我们仅向16周岁及以上的用户提供求职招聘服务）。
    type: individual
  - text: 合法设立并存续的企业、机关、社团、事业单位和其他组织
    type: business
  minimum_age:
    text: 我们仅向16周岁及以上的用户提供求职招聘服务
    value: '16'
  restricted_uses:
  - summary: Illegal activity by employers
    text: 涉嫌传销、赌博、色情、暴力、邪教与封建迷信、欺诈、非法集资等违法犯罪情形的
  verification:
    approval_required: true
    kyb: true
    kyc: true
    text: 招聘者用户需补充个人信息、招聘者单位信息，完成个人实名认证并提供单位相应资质等材料
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Lagou
provenance_date: '2026-11-09'
provider_name: Lagou
provider_slug: lagou
slug: lagou-eligibility
source_date: '2026-11-09'
source_filename: lagou-eligibility.yml
source_heading: Eligibility
source_page: https://www.lagou.com/privacy.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Lagou\naid: lagou\nurl: https://www.lagou.com/privacy.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: 具备完全民事行为能力的自然人（我们仅向16周岁及以上的用户提供求职招聘服务）。\n- type: business\n  text: 合法设立并存续的企业、机关、社团、事业单位和其他组织\nrestricted_uses:\n- summary: Illegal activity by employers\n  text: 涉嫌传销、赌博、色情、暴力、邪教与封建迷信、欺诈、非法集资等违法犯罪情形的\nverification:\n  kyc: true\n  kyb: true\n  approval_required: true\n  text: 招聘者用户需补充个人信息、招聘者单位信息，完成个人实名认证并提供单位相应资质等材料\nminimum_age:\n  value: '16'\n  text: 我们仅向16周岁及以上的用户提供求职招聘服务\n"
source_yaml_url: https://artifacts.apis.io/lagou/eligibility/lagou-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Lagou's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Recruiting
- Job
- Hiring
- Human Resources
- Talent
- Careers
- Employment
- Education
- China
---
