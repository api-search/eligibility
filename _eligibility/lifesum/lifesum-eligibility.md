---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Service is only available for your private use and is not intended for commercial use.
    type: individual
  minimum_age:
    text: To use Lifesum, you must be at least 13 years old.
    value: '13'
  restricted_uses:
  - summary: No commercial use
    text: You are not allowed to engage in any commercial activities, advertise and/or provide hints (such as links) on where commercial activities are present through our Services.
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
name: Lifesum
provenance_date: '2026-11-09'
provider_name: Lifesum
provider_slug: lifesum
slug: lifesum-eligibility
source_date: '2026-11-09'
source_filename: lifesum-eligibility.yml
source_heading: Eligibility
source_page: https://lifesum.com/policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Lifesum\naid: lifesum\nurl: https://lifesum.com/policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Service is only available for your private use and is not intended for commercial use.\nrestricted_uses:\n- summary: No commercial use\n  text: You are not allowed to engage in any commercial activities, advertise and/or provide hints (such as links)\n    on where commercial activities are present through our Services.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n\
  \  text: To use Lifesum, you must be at least 13 years old.\n"
source_yaml_url: https://artifacts.apis.io/lifesum/eligibility/lifesum-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Lifesum's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Health
- Nutrition
- Fitness
- Wellness
- Mobile App
- Consumer
- FoodTracking
---
