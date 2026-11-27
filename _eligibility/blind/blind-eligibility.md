---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: you are an individual not prohibited from receiving the Service under the laws of the United States or any other applicable jurisdiction
    type: individual
  minimum_age:
    text: You may not use the Service unless you are over the age of majority under the laws applicable to you.
    value: age of majority
  restricted_uses:
  - summary: Minors cannot buy or use Items
    text: Users who are not the age of majority under applicable law are prohibited from purchasing or using Items on Blind.
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
name: Blind
provenance_date: '2026-11-09'
provider_name: Blind
provider_slug: blind
slug: blind-eligibility
source_date: '2026-11-09'
source_filename: blind-eligibility.yml
source_heading: Eligibility
source_page: https://us.teamblind.com/setting/term
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Blind\naid: blind\nurl: https://us.teamblind.com/setting/term\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: you are an individual not prohibited from receiving the Service under the laws of the United States or any\n    other applicable jurisdiction\nrestricted_uses:\n- summary: Minors cannot buy or use Items\n  text: Users who are not the age of majority under applicable law are prohibited from purchasing or using Items\n    on Blind.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: age of majority\n  text: You may not use the Service unless you are over the age of majority under the laws applicable to you.\n"
source_yaml_url: https://artifacts.apis.io/blind/eligibility/blind-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Blind's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer
- Social Network
- Professional Network
- Community
- Anonymous
- Careers
- Workplace
---
