---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The price is displayed in the app before purchase and may vary by country; no served or excluded countries are named.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Personal use design
    text: The app is designed for personal use.
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
name: Cesure
provenance_date: '2026-11-09'
provider_name: Cesure
provider_slug: cesure-app
slug: cesure-app-eligibility
source_date: '2026-11-09'
source_filename: cesure-app-eligibility.yml
source_heading: Eligibility
source_page: https://cesure.app/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cesure\naid: cesure-app\nurl: https://cesure.app/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The price is displayed in the app before purchase and may vary by country; no served or excluded countries\n    are named.\nentity_types: []\nrestricted_uses:\n- summary: Personal use design\n  text: The app is designed for personal use.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/cesure-app/eligibility/cesure-app-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from Cesure's own page on 2026-11-09.
synthetic: false
tags:
- Music
- Guitar
- Artificial Intelligence
- Web App
- Collaboration
---
