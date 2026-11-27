---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 为商业地产、购物中心、品牌连锁店、银行网点、汽车 4S 店、停车场、机场、景区、运营商、高铁等实体垂直行业的客户
    type: business
  minimum_age:
    text: null
    value: null
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
name: Aibee
provenance_date: '2026-11-09'
provider_name: Aibee
provider_slug: aibee
slug: aibee-eligibility
source_date: '2026-11-09'
source_filename: aibee-eligibility.yml
source_heading: Eligibility
source_page: https://www.aibee.cn/legal.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Aibee\naid: aibee\nurl: https://www.aibee.cn/legal.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: 为商业地产、购物中心、品牌连锁店、银行网点、汽车 4S 店、停车场、机场、景区、运营商、高铁等实体垂直行业的客户\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/aibee/eligibility/aibee-eligibility.yml
stated_fields:
- entity_types
summary_line: 1 quoted statement, read from Aibee's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Computer Vision
- Indoor Mapping
- Indoor Navigation
- Augmented Reality
- Retail Technology
- Commercial Real Estate
- Smart Parking
- Location Services
- SDK
- China
---
