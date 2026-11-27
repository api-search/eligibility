---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: insofar as the use or purchase of the YAZIO App cannot be assigned primarily to the User’s commercial or self-employed professional activity.
    type: individual
  - text: any natural or legal person or partnership with legal capacity that acts in exercise of its trade, business, or profession when using the YAZIO App or entering into the contract
    type: business
  minimum_age:
    text: You must be at least 16 years of age to use our App, unless a parent or legal guardian has consented to the installation and subsequent use of our App in accordance with the applicable law.
    value: '16'
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
name: YAZIO
provenance_date: '2026-11-10'
provider_name: YAZIO
provider_slug: yazio
slug: yazio-eligibility
source_date: '2026-11-10'
source_filename: yazio-eligibility.yml
source_heading: Eligibility
source_page: https://help.yazio.com/hc/en-us/articles/203444951-Terms-of-Use-Privacy-Policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: YAZIO\naid: yazio\nurl: https://help.yazio.com/hc/en-us/articles/203444951-Terms-of-Use-Privacy-Policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: insofar as the use or purchase of the YAZIO App cannot be assigned primarily to the User’s commercial or\n    self-employed professional activity.\n- type: business\n  text: any natural or legal person or partnership with legal capacity that acts in exercise of its trade, business,\n    or profession when using the YAZIO App or entering into the contract\nrestricted_uses:\
  \ []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: You must be at least 16 years of age to use our App, unless a parent or legal guardian has consented to\n    the installation and subsequent use of our App in accordance with the applicable law.\n"
source_yaml_url: https://artifacts.apis.io/yazio/eligibility/yazio-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from YAZIO's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Health
- Digital Health
- Nutrition
- Calorie Tracking
- Weight Management
- Intermittent Fasting
- Fitness
- Consumer Health
- Mobile App
- Germany
---
