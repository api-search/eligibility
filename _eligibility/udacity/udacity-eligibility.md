---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: a "Visitor," meaning any individual that browses any of our Services
    type: individual
  minimum_age:
    text: If you under the age of 18, but at least 13 years of age, you represent and agree that you are an emancipated minor or possess legal parental or guardian consent to use the Services
    value: '13'
  restricted_uses:
  - summary: Commercial use of Content
    text: Any use of such information for commercial purposes is strictly prohibited.
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
name: Udacity
provenance_date: '2026-11-10'
provider_name: Udacity
provider_slug: udacity
slug: udacity-eligibility
source_date: '2026-11-10'
source_filename: udacity-eligibility.yml
source_heading: Eligibility
source_page: https://www.udacity.com/en-US/legal/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Udacity\naid: udacity\nurl: https://www.udacity.com/en-US/legal/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: a \"Visitor,\" meaning any individual that browses any of our Services\nrestricted_uses:\n- summary: Commercial use of Content\n  text: Any use of such information for commercial purposes is strictly prohibited.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: If you under the age of 18, but at least 13 years of age, you\
  \ represent and agree that you are an emancipated\n    minor or possess legal parental or guardian consent to use the Services\n"
source_yaml_url: https://artifacts.apis.io/udacity/eligibility/udacity-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Udacity's own page on 2026-11-10.
synthetic: false
tags:
- E-Learning
- Upskilling
- Nanodegrees
- Tech Education
- Workforce Development
- Generative AI Training
- AI Agents
- Data Science
- Cloud Computing
- Cybersecurity
- Autonomous Systems
- Self-Driving Cars
- Accenture
- LearnVantage
---
