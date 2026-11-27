---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: This service is currently not intended for users in the European Union (EU) or the European Economic Area (EEA).
  minimum_age:
    text: You must be at least 13 years old to use our Services.
    value: '13'
  restricted_uses:
  - summary: Children under 13
    text: Our Services are not intended for children under the age of 13.
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
name: App-CM
provenance_date: '2026-11-09'
provider_name: App-CM
provider_slug: app-cm
slug: app-cm-eligibility
source_date: '2026-11-09'
source_filename: app-cm-eligibility.yml
source_heading: Eligibility
source_page: https://www.app-cm.co.jp/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: App-CM\naid: app-cm\nurl: https://www.app-cm.co.jp/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: This service is currently not intended for users in the European Union (EU) or the European Economic Area\n    (EEA).\nentity_types: []\nrestricted_uses:\n- summary: Children under 13\n  text: Our Services are not intended for children under the age of 13.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You must be at least 13 years old to use our Services.\n"
source_yaml_url: https://artifacts.apis.io/app-cm/eligibility/app-cm-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from App-CM's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Advertising
- Video Advertising
- AdTech
- Mobile
- Consumer App
- Platform
- Japan
---
