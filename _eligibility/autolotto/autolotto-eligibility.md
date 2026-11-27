---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: be at least eighteen (18) years of age or the age of majority in your Jurisdiction of residence, whichever is greater
    type: individual
  minimum_age:
    text: be at least eighteen (18) years of age or the age of majority in your Jurisdiction of residence, whichever is greater
    value: '18'
  restricted_uses:
  - summary: Unlawful gambling
    text: Use the Lottery.com App in a manner prohibited by applicable laws or regulations, including, without limitation, in connection with any form of unlawful gambling.
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: The Company reserves the right to verify your age, identity and eligibility at any time.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: AutoLotto
provenance_date: '2026-11-09'
provider_name: AutoLotto
provider_slug: autolotto
slug: autolotto-eligibility
source_date: '2026-11-09'
source_filename: autolotto-eligibility.yml
source_heading: Eligibility
source_page: https://lottery.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AutoLotto\naid: autolotto\nurl: https://lottery.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: be at least eighteen (18) years of age or the age of majority in your Jurisdiction of residence, whichever\n    is greater\nrestricted_uses:\n- summary: Unlawful gambling\n  text: Use the Lottery.com App in a manner prohibited by applicable laws or regulations, including, without limitation,\n    in connection with any form of unlawful gambling.\nverification:\n  kyc: true\n  kyb: null\n  approval_required:\
  \ null\n  text: The Company reserves the right to verify your age, identity and eligibility at any time.\nminimum_age:\n  value: '18'\n  text: be at least eighteen (18) years of age or the age of majority in your Jurisdiction of residence, whichever\n    is greater\n"
source_yaml_url: https://artifacts.apis.io/autolotto/eligibility/autolotto-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from AutoLotto's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Lottery
- Gaming
- Consumer
- Mobile
- Data Licensing
- Entertainment
---
