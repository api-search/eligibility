---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You may not access or use the Services or accept the terms if you are not at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: No use for competing services
    text: you will not use the Services in order to provide similar services to any third party or for competing with our Service.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: In order to fully access and use the Services (including paid/subscription services ), you must register for an account
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Apptopia
provenance_date: '2026-11-09'
provider_name: Apptopia
provider_slug: apptopia
slug: apptopia-eligibility
source_date: '2026-11-09'
source_filename: apptopia-eligibility.yml
source_heading: Eligibility
source_page: https://apptopia.com/en/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Apptopia\naid: apptopia\nurl: https://apptopia.com/en/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: No use for competing services\n  text: you will not use the Services in order to provide similar services to any third party or for competing with\n    our Service.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: In order to fully access and use the Services (including paid/subscription services ), you must register\n    for an account\nminimum_age:\n  value: '18'\n  text: You may not access\
  \ or use the Services or accept the terms if you are not at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/apptopia/eligibility/apptopia-eligibility.yml
stated_fields:
- restricted_uses
- verification
- minimum_age
summary_line: 3 quoted statements, read from Apptopia's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Mobile
- App Store Intelligence
- Market Intelligence
- Alternative Data
- Analytics
- Consumer Insights
- Advertising
---
