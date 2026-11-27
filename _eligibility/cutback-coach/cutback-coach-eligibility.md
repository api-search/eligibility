---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Services, including the Healthcare Services, are not available in all 50 states. By using the Services, you represent and warrant that you are located in a state where we operate.
  entity_types:
  - text: We do not permit individuals under 21 years of age to become registered users of our Services.
    type: individual
  minimum_age:
    text: By using the Services, you represent and warrant that you are at least 21 years of age
    value: '21'
  restricted_uses:
  - summary: Individuals with AUD diagnosis
    text: The Services are not intended for individuals that have been diagnosed with or currently undergoing treatment for Alcohol Use Disorder (AUD) or any other diagnosis regarding alcohol.
  - summary: Pregnancy or breastfeeding
    text: We do not recommend that individuals who are pregnant or breastfeeding use our Services, but instead consult directly with their physicians.
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
name: Cutback Coach
provenance_date: '2026-11-09'
provider_name: Cutback Coach
provider_slug: cutback-coach
slug: cutback-coach-eligibility
source_date: '2026-11-09'
source_filename: cutback-coach-eligibility.yml
source_heading: Eligibility
source_page: https://www.sunnyside.co/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cutback Coach\naid: cutback-coach\nurl: https://www.sunnyside.co/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Services, including the Healthcare Services, are not available in all 50 states. By using the Services,\n    you represent and warrant that you are located in a state where we operate.\nentity_types:\n- type: individual\n  text: We do not permit individuals under 21 years of age to become registered users of our Services.\nrestricted_uses:\n- summary: Individuals with AUD diagnosis\n  text: The Services are not intended for individuals that have been diagnosed\
  \ with or currently undergoing treatment\n    for Alcohol Use Disorder (AUD) or any other diagnosis regarding alcohol.\n- summary: Pregnancy or breastfeeding\n  text: We do not recommend that individuals who are pregnant or breastfeeding use our Services, but instead consult\n    directly with their physicians.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '21'\n  text: By using the Services, you represent and warrant that you are at least 21 years of age\n"
source_yaml_url: https://artifacts.apis.io/cutback-coach/eligibility/cutback-coach-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Cutback Coach's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Health
- Digital Health
- Alcohol
- Wellness
---
