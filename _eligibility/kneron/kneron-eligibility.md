---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: 如果您要在KNEO電子商務進行使用或消費，您必須先完成Kneron帳戶登記作業
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Kneron
provenance_date: '2026-11-09'
provider_name: Kneron
provider_slug: kneron
slug: kneron-eligibility
source_date: '2026-11-09'
source_filename: kneron-eligibility.yml
source_heading: Eligibility
source_page: https://kneo.kneron.com/conditions-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Kneron\naid: kneron\nurl: https://kneo.kneron.com/conditions-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: 如果您要在KNEO電子商務進行使用或消費，您必須先完成Kneron帳戶登記作業\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/kneron/eligibility/kneron-eligibility.yml
stated_fields:
- verification
summary_line: 1 quoted statement, read from Kneron's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Edge AI
- Semiconductors
- Neural Processing Unit
- Machine Learning
- Computer Vision
- AIoT
- Hardware
- LLM
- On-Premise AI
- SDK
- Embedded Systems
---
