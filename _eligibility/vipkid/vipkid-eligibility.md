---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: 'By accessing or using the VIPKid website, you: 1) confirm that you are of legal age to access the VIPKid Platform'
    value: null
  restricted_uses:
  - summary: Personal noncommercial use only
    text: solely for your personal, noncommercial use
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
name: VIPKid
provenance_date: '2026-11-10'
provider_name: VIPKid
provider_slug: vipkid
slug: vipkid-eligibility
source_date: '2026-11-10'
source_filename: vipkid-eligibility.yml
source_heading: Eligibility
source_page: https://teach.vipteacher.com/landing/teach-terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: VIPKid\naid: vipkid\nurl: https://teach.vipteacher.com/landing/teach-terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Personal noncommercial use only\n  text: solely for your personal, noncommercial use\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: 'By accessing or using the VIPKid website, you: 1) confirm that you are of legal age to access the VIPKid\n    Platform'\n"
source_yaml_url: https://artifacts.apis.io/vipkid/eligibility/vipkid-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from VIPKid's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Education
- EdTech
- E-Learning
- Language Learning
- English Language Teaching
- Tutoring
- K-12
- Consumer
- China
---
