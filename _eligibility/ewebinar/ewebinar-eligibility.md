---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: The Services are intended solely for users who are at least 13 years of age or older
    value: '13'
  restricted_uses:
  - summary: Unsolicited advertising and spam
    text: consists of any unsolicited or unauthorized advertising, solicitations, promotional materials, “junk mail,” “spam,” “chain letters,” “pyramid schemes,”
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
name: eWebinar
provenance_date: '2026-11-09'
provider_name: eWebinar
provider_slug: ewebinar
slug: ewebinar-eligibility
source_date: '2026-11-09'
source_filename: ewebinar-eligibility.yml
source_heading: Eligibility
source_page: https://ewebinar.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: eWebinar\naid: ewebinar\nurl: https://ewebinar.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unsolicited advertising and spam\n  text: consists of any unsolicited or unauthorized advertising, solicitations, promotional materials, “junk mail,”\n    “spam,” “chain letters,” “pyramid schemes,”\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: The Services are intended solely for users who are at least 13 years of age or older\n"
source_yaml_url: https://artifacts.apis.io/ewebinar/eligibility/ewebinar-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from eWebinar's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Webinar
- Video
- On-Demand
- Software-as-a-Service
---
