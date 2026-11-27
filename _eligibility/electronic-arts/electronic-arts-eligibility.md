---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You must be a resident of a country where use of EA Services is permitted.
  minimum_age:
    text: You must be at least 13 years of age (or the minimum age of your country of residence) to create an EA Account.
    value: '13'
  restricted_uses:
  - summary: Non-commercial use only
    text: for your non-commercial use
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: To create an EA Account, you must have a valid email address, and provide truthful and accurate information.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Electronic Arts
provenance_date: '2026-11-09'
provider_name: Electronic Arts
provider_slug: electronic-arts
slug: electronic-arts-eligibility
source_date: '2026-11-09'
source_filename: electronic-arts-eligibility.yml
source_heading: Eligibility
source_page: https://www.ea.com/legal/user-agreement
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Electronic Arts\naid: electronic-arts\nurl: https://www.ea.com/legal/user-agreement\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You must be a resident of a country where use of EA Services is permitted.\nentity_types: []\nrestricted_uses:\n- summary: Non-commercial use only\n  text: for your non-commercial use\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: To create an EA Account, you must have a valid email address, and provide truthful and accurate information.\nminimum_age:\n  value: '13'\n  text: You must be at least 13 years of age (or the minimum\
  \ age of your country of residence) to create an EA Account.\n"
source_yaml_url: https://artifacts.apis.io/electronic-arts/eligibility/electronic-arts-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Electronic Arts's own page on 2026-11-09.
synthetic: false
tags:
- Gaming
- Video Games
- Entertainment
- Consumer
- Player Services
- Fortune 1000
---
