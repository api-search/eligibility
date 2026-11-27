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
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: Der Kaufinteressent wird Homeday eine Kopie seines Personalausweises oder Reisepasses zukommen lassen (Vorder- und Rückseite).
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Homeday
provenance_date: '2026-11-09'
provider_name: Homeday
provider_slug: homeday
slug: homeday-eligibility
source_date: '2026-11-09'
source_filename: homeday-eligibility.yml
source_heading: Eligibility
source_page: https://www.homeday.de/de/agb-fuer-kaufinteressenten/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Homeday\naid: homeday\nurl: https://www.homeday.de/de/agb-fuer-kaufinteressenten/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: Der Kaufinteressent wird Homeday eine Kopie seines Personalausweises oder Reisepasses zukommen lassen (Vorder-\n    und Rückseite).\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/homeday/eligibility/homeday-eligibility.yml
stated_fields:
- verification
summary_line: 1 quoted statement, read from Homeday's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Real Estate
- PropTech
- Germany
- Brokerage
- Mortgage
- Property Valuation
---
