---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: This website is intended for use by children aged 13 and over, as well as their parents or legal guardians.
    value: '13'
  restricted_uses:
  - summary: Personal non-commercial use only
    text: Our Website is for your personal and non-commercial use only.
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
name: Animaj
provenance_date: '2026-11-09'
provider_name: Animaj
provider_slug: animaj
slug: animaj-eligibility
source_date: '2026-11-09'
source_filename: animaj-eligibility.yml
source_heading: Eligibility
source_page: https://www.animaj.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Animaj\naid: animaj\nurl: https://www.animaj.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Personal non-commercial use only\n  text: Our Website is for your personal and non-commercial use only.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: This website is intended for use by children aged 13 and over, as well as their parents or legal guardians.\n"
source_yaml_url: https://artifacts.apis.io/animaj/eligibility/animaj-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Animaj's own page on 2026-11-09.
synthetic: false
tags:
- Animal Health
- Data Platform
- Software-as-a-Service
- Innovation
---
