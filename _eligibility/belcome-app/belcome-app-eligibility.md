---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Service is for businesses worldwide and the people who work for them, where the Service can lawfully be provided.
  entity_types:
  - text: The Service is for businesses worldwide and the people who work for them, where the Service can lawfully be provided.
    type: business
  - text: You must be at least 18 years old to create an account.
    type: individual
  minimum_age:
    text: You must be at least 18 years old to create an account.
    value: '18'
  restricted_uses:
  - summary: Protected health information requires BAA
    text: you must accept the Belcome Business Associate Agreement before you store protected health information in the Service.
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
name: Belcome
provenance_date: '2026-11-09'
provider_name: Belcome
provider_slug: belcome-app
slug: belcome-app-eligibility
source_date: '2026-11-09'
source_filename: belcome-app-eligibility.yml
source_heading: Eligibility
source_page: https://www.belcome.app/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Belcome\naid: belcome-app\nurl: https://www.belcome.app/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Service is for businesses worldwide and the people who work for them, where the Service can lawfully\n    be provided.\nentity_types:\n- type: business\n  text: The Service is for businesses worldwide and the people who work for them, where the Service can lawfully\n    be provided.\n- type: individual\n  text: You must be at least 18 years old to create an account.\nrestricted_uses:\n- summary: Protected health information requires BAA\n  text: you must accept the Belcome\
  \ Business Associate Agreement before you store protected health information in\n    the Service.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to create an account.\n"
source_yaml_url: https://artifacts.apis.io/belcome-app/eligibility/belcome-app-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Belcome's own page on 2026-11-09.
synthetic: false
tags:
- Booking
- Salon
- Spa
- Software-as-a-Service
- Healthcare
---
