---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: The Site, Services and Content are not intended for and should not be used by Children under the age of 13.
    value: '13'
  restricted_uses:
  - summary: Competitors and litigants barred
    text: you are not, and are not acting on behalf of, any competitor or prospective competitor of Cronometer or its affiliates or subsidiaries
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
name: Cronometer
provenance_date: '2026-11-09'
provider_name: Cronometer
provider_slug: cronometer
slug: cronometer-eligibility
source_date: '2026-11-09'
source_filename: cronometer-eligibility.yml
source_heading: Eligibility
source_page: https://cronometer.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cronometer\naid: cronometer\nurl: https://cronometer.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Competitors and litigants barred\n  text: you are not, and are not acting on behalf of, any competitor or prospective competitor of Cronometer or\n    its affiliates or subsidiaries\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: The Site, Services and Content are not intended for and should not be used by Children under the age\
  \ of\n    13.\n"
source_yaml_url: https://artifacts.apis.io/cronometer/eligibility/cronometer-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Cronometer's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Nutrition
- Health
- Fitness
- Calorie Counter
- Diet Tracking
- Mobile App
- Wellness
---
