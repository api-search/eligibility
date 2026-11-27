---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old to create an account on Datefit and use the Services.
    type: individual
  minimum_age:
    text: You must be at least 18 years old to create an account on Datefit and use the Services.
    value: '18'
  restricted_uses:
  - summary: Commercial activity in content
    text: Used for the purpose of advertising, conducting, or soliciting commercial activities
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: To create a Datefit account, you may sign in using your Facebook login, your telephone number or your email address.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Datefit
provenance_date: '2026-11-09'
provider_name: Datefit
provider_slug: datefit
slug: datefit-eligibility
source_date: '2026-11-09'
source_filename: datefit-eligibility.yml
source_heading: Eligibility
source_page: https://datefit.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Datefit\naid: datefit\nurl: https://datefit.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old to create an account on Datefit and use the Services.\nrestricted_uses:\n- summary: Commercial activity in content\n  text: Used for the purpose of advertising, conducting, or soliciting commercial activities\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: To create a Datefit account, you may sign in using your Facebook login, your telephone number or your email\n\
  \    address.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to create an account on Datefit and use the Services.\n"
source_yaml_url: https://artifacts.apis.io/datefit/eligibility/datefit-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Datefit's own page on 2026-11-09.
synthetic: false
tags:
- Health
- Wellness
- Fitness
- Data Analytics
---
