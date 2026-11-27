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
    kyc: null
    text: When you opt-in to the service, we will send you a message asking you to confirm your signup.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Air Force Reserve
provenance_date: '2026-11-09'
provider_name: Air Force Reserve
provider_slug: air-force-reserve
slug: air-force-reserve-eligibility
source_date: '2026-11-09'
source_filename: air-force-reserve-eligibility.yml
source_heading: Eligibility
source_page: https://www.airforce.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Air Force Reserve\naid: air-force-reserve\nurl: https://www.airforce.com/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: When you opt-in to the service, we will send you a message asking you to confirm your signup.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/air-force-reserve/eligibility/air-force-reserve-eligibility.yml
stated_fields:
- verification
summary_line: 1 quoted statement, read from Air Force Reserve's own page on 2026-11-09.
synthetic: false
tags:
- Federal Government
- Military
- Defense
- Air Force
- United States Government
---
