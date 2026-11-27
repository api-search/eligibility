---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: BabylonAI GmbH provides the Services if you are resident in the EEA or Switzerland; BabylonAI Inc. provides them if you're not a resident of the EEA or Switzerland.
  entity_types:
  - text: You must be at least 14 years old or the minimum age required in your country to consent to use the Services.
    type: individual
  minimum_age:
    text: You must be at least 14 years old or the minimum age required in your country to consent to use the Services. If you are below the age of 18, you must obtain permission from your parent or legal guardian to use the Services
    value: '14'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You must provide accurate and complete information to register for an account to use our Services.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Rex
provenance_date: '2026-11-10'
provider_name: Rex
provider_slug: rex-inc
slug: rex-inc-eligibility
source_date: '2026-11-10'
source_filename: rex-inc-eligibility.yml
source_heading: Eligibility
source_page: https://www.rex.fit/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Rex\naid: rex-inc\nurl: https://www.rex.fit/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: BabylonAI GmbH provides the Services if you are resident in the EEA or Switzerland; BabylonAI Inc. provides\n    them if you're not a resident of the EEA or Switzerland.\nentity_types:\n- type: individual\n  text: You must be at least 14 years old or the minimum age required in your country to consent to use the Services.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You must provide accurate and complete information to register\
  \ for an account to use our Services.\nminimum_age:\n  value: '14'\n  text: You must be at least 14 years old or the minimum age required in your country to consent to use the Services.\n    If you are below the age of 18, you must obtain permission from your parent or legal guardian to use the Services\n"
source_yaml_url: https://artifacts.apis.io/rex-inc/eligibility/rex-inc-eligibility.yml
stated_fields:
- countries
- entity_types
- verification
- minimum_age
summary_line: 4 quoted statements, read from Rex's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Health
- Fitness
- Nutrition
- Artificial Intelligence
- Computer Vision
- Wearables
- Y Combinator
---
