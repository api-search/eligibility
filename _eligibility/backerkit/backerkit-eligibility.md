---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Prohibited Projects
    text: Project Creators are not permitted to create a Project to solicit information from Users for illegal activities, to cause harm to people or property, or to scam others.
  - summary: Prohibited Rewards
    text: 'Project Creators are not permitted to use BackerKit to offer or provide any of the following as a Reward:'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Diaspora is not responsible for authenticating or confirming the accuracy of any information about any User.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Backerkit
provenance_date: '2026-11-09'
provider_name: Backerkit
provider_slug: backerkit
slug: backerkit-eligibility
source_date: '2026-11-09'
source_filename: backerkit-eligibility.yml
source_heading: Eligibility
source_page: https://www.backerkit.com/terms_of_service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Backerkit\naid: backerkit\nurl: https://www.backerkit.com/terms_of_service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Prohibited Projects\n  text: Project Creators are not permitted to create a Project to solicit information from Users for illegal activities,\n    to cause harm to people or property, or to scam others.\n- summary: Prohibited Rewards\n  text: 'Project Creators are not permitted to use BackerKit to offer or provide any of the following as a Reward:'\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: Diaspora is not responsible for authenticating or confirming the accuracy of any information about any User.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/backerkit/eligibility/backerkit-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 3 quoted statements, read from Backerkit's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Crowdfunding
- Pledge Management
- Fulfillment
- Creator Economy
- Payments
- E-Commerce
- Y Combinator
---
