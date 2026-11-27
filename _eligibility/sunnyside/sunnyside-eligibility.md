---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Services, including the Healthcare Services, are not available in all 50 states. By using the Services, you represent and warrant that you are located in a state where we operate.
  entity_types:
  - text: We do not permit individuals under 21 years of age to become registered users of our Services.
    type: individual
  minimum_age:
    text: We do not permit individuals under 21 years of age to become registered users of our Services.
    value: '21'
  restricted_uses:
  - summary: Not for pregnant or breastfeeding users
    text: We do not recommend that individuals who are pregnant or breastfeeding use our Services
  - summary: Not for individuals with Alcohol Use Disorder treatment
    text: The Services are not intended for individuals that have been diagnosed with or currently undergoing treatment for Alcohol Use Disorder (AUD) or any other diagnosis regarding alcohol.
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
name: Sunnyside
provenance_date: '2026-11-10'
provider_name: Sunnyside
provider_slug: sunnyside
slug: sunnyside-eligibility
source_date: '2026-11-10'
source_filename: sunnyside-eligibility.yml
source_heading: Eligibility
source_page: https://www.sunnyside.co/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Sunnyside\naid: sunnyside\nurl: https://www.sunnyside.co/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Services, including the Healthcare Services, are not available in all 50 states. By using the Services,\n    you represent and warrant that you are located in a state where we operate.\nentity_types:\n- type: individual\n  text: We do not permit individuals under 21 years of age to become registered users of our Services.\nrestricted_uses:\n- summary: Not for pregnant or breastfeeding users\n  text: We do not recommend that individuals who are pregnant or breastfeeding\
  \ use our Services\n- summary: Not for individuals with Alcohol Use Disorder treatment\n  text: The Services are not intended for individuals that have been diagnosed with or currently undergoing treatment\n    for Alcohol Use Disorder (AUD) or any other diagnosis regarding alcohol.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '21'\n  text: We do not permit individuals under 21 years of age to become registered users of our Services.\n"
source_yaml_url: https://artifacts.apis.io/sunnyside/eligibility/sunnyside-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Sunnyside's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Digital Health
- Health and Wellness
- Telehealth
- Behavior Change
- Alcohol Moderation
- Consumer App
---
