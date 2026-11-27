---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful, abusive or offensive community content
    text: Jogellenes, sértő, reklámjellegű vagy szükségtelen személyes adatot tartalmazó bejegyzés nem jelenik meg.
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
name: EU Money
provenance_date: '2026-11-09'
provider_name: EU Money
provider_slug: eumoney-hu
slug: eumoney-hu-eligibility
source_date: '2026-11-09'
source_filename: eumoney-hu-eligibility.yml
source_heading: Eligibility
source_page: https://eumoney.hu/felhasznalasi-feltetelek
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: EU Money\naid: eumoney-hu\nurl: https://eumoney.hu/felhasznalasi-feltetelek\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful, abusive or offensive community content\n  text: Jogellenes, sértő, reklámjellegű vagy szükségtelen személyes adatot tartalmazó bejegyzés nem jelenik meg.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/eumoney-hu/eligibility/eumoney-hu-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from EU Money's own page on 2026-11-09.
synthetic: false
tags:
- Fintech
- Grants
- EU
- Business
- Analytics
---
