---
api_specs:
- filename: 31huiyi-openapi.postman_collection.json
  format: json
  label: 31 OpenAPI
  slug: 31huiyi-openapi
  spec_type: Postman
  url: https://artifacts.apis.io/31huiyi/postman/31huiyi-openapi.postman_collection.json
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: 如果您是不满14周岁的儿童，请不要使用31会议服务
    value: '14'
  restricted_uses:
  - summary: no unlawful activity
    text: 不得以任何方式利用31会议服务从事违反中国法律法规的活动
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
name: 31huiyi
provenance_date: '2026-11-09'
provider_name: 31huiyi
provider_slug: 31huiyi
slug: 31huiyi-eligibility
source_date: '2026-11-09'
source_filename: 31huiyi-eligibility.yml
source_heading: Eligibility
source_page: https://www.31huiyi.com/special/termsofservice
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: 31huiyi\naid: 31huiyi\nurl: https://www.31huiyi.com/special/termsofservice\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: no unlawful activity\n  text: 不得以任何方式利用31会议服务从事违反中国法律法规的活动\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '14'\n  text: 如果您是不满14周岁的儿童，请不要使用31会议服务\n"
source_yaml_url: https://artifacts.apis.io/31huiyi/eligibility/31huiyi-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from 31huiyi's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Event
- Event Management
- Conferences
- Exhibitions
- Registration
- Check-in
- Scheduling
- Ticketing
- Software-as-a-Service
- China
---
