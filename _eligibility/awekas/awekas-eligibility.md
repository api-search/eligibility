---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Terms regulate the relationship between AWEKAS and consumers or business customers worldwide.
  entity_types:
  - text: The Terms regulate the relationship between AWEKAS and consumers or business customers worldwide.
    type: individual
  - text: The Terms regulate the relationship between AWEKAS and consumers or business customers worldwide.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Services requiring a licence or subscription
    text: Certain services require an active license or subscription, available through the AWEKAS Shop or official app stores.
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
name: AWEKAS
provenance_date: '2026-11-09'
provider_name: AWEKAS
provider_slug: awekas
slug: awekas-eligibility
source_date: '2026-11-09'
source_filename: awekas-eligibility.yml
source_heading: Eligibility
source_page: https://www.awekas.at/main/en/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AWEKAS\naid: awekas\nurl: https://www.awekas.at/main/en/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Terms regulate the relationship between AWEKAS and consumers or business customers worldwide.\nentity_types:\n- type: individual\n  text: The Terms regulate the relationship between AWEKAS and consumers or business customers worldwide.\n- type: business\n  text: The Terms regulate the relationship between AWEKAS and consumers or business customers worldwide.\nrestricted_uses:\n- summary: Services requiring a licence or subscription\n  text: Certain services require an\
  \ active license or subscription, available through the AWEKAS Shop or official\n    app stores.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/awekas/eligibility/awekas-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from AWEKAS's own page on 2026-11-09.
synthetic: false
tags:
- Weather Data
- Private Weather Stations
- Weather Map
- Weather App
- Community Network
---
