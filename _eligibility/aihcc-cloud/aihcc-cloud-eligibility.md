---
api_specs:
- filename: aihcc-cloud-openapi-generated.yml
  format: yaml
  label: AIHCC API
  slug: aihcc-cloud-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aihcc-cloud/openapi/_ae-authored/aihcc-cloud-openapi-generated.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Illegal activity
    text: 不得利用本服务从事违反法律法规的活动，不得提交依法禁止传播的内容。
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: 您应使用真实有效的邮箱或手机号注册，妥善保管账号与 API Key；
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: AIHCC
provenance_date: '2026-11-09'
provider_name: AIHCC
provider_slug: aihcc-cloud
slug: aihcc-cloud-eligibility
source_date: '2026-11-09'
source_filename: aihcc-cloud-eligibility.yml
source_heading: Eligibility
source_page: https://aihcc.cloud/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AIHCC\naid: aihcc-cloud\nurl: https://aihcc.cloud/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Illegal activity\n  text: 不得利用本服务从事违反法律法规的活动，不得提交依法禁止传播的内容。\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: 您应使用真实有效的邮箱或手机号注册，妥善保管账号与 API Key；\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/aihcc-cloud/eligibility/aihcc-cloud-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from AIHCC's own page on 2026-11-09.
synthetic: false
tags:
- AI Safety
- Agent Tools
- Hallucination Detection
- Prompt Injection
- Chinese
---
