---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You may not use the Service if you are a resident of a country embargoed by the United States, or are a foreign person or entity blocked or denied by the United States government.
  entity_types:
  - text: You may use the Service only if you can form a binding contract with Blue Fever
    type: individual
  minimum_age:
    text: Any use or access to the Service by anyone under 13 is strictly prohibited and in violation of this Agreement.
    value: '13'
  restricted_uses:
  - summary: Noncommercial personal use only
    text: personal, noncommercial use only and as permitted by the features of the Service
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
name: Blue Fever
provenance_date: '2026-11-09'
provider_name: Blue Fever
provider_slug: blue-fever
slug: blue-fever-eligibility
source_date: '2026-11-09'
source_filename: blue-fever-eligibility.yml
source_heading: Eligibility
source_page: https://www.bluefever.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Blue Fever\naid: blue-fever\nurl: https://www.bluefever.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You may not use the Service if you are a resident of a country embargoed by the United States, or are a\n    foreign person or entity blocked or denied by the United States government.\nentity_types:\n- type: individual\n  text: You may use the Service only if you can form a binding contract with Blue Fever\nrestricted_uses:\n- summary: Noncommercial personal use only\n  text: personal, noncommercial use only and as permitted by the features of the Service\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: Any use or access to the Service by anyone under 13 is strictly prohibited and in violation of this Agreement.\n"
source_yaml_url: https://artifacts.apis.io/blue-fever/eligibility/blue-fever-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Blue Fever's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Mental Health
- Social
- Wellness
- Artificial Intelligence
- Consumer App
- Teens
- Emotional Support
---
