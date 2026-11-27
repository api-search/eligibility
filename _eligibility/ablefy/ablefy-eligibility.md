---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: Only natural persons or legal entities, partnerships and non-profit organizations that are of legal age and have unlimited legal capacity can register.
    value: null
  restricted_uses:
  - summary: Prohibited business areas
    text: The customer shall ensure that its offers are not included in the current list of restricted and prohibited business activities.
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
name: ablefy
provenance_date: '2026-11-09'
provider_name: ablefy
provider_slug: ablefy
slug: ablefy-eligibility
source_date: '2026-11-09'
source_filename: ablefy-eligibility.yml
source_heading: Eligibility
source_page: https://myablefy.com/terms?locale=en
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ablefy\naid: ablefy\nurl: https://myablefy.com/terms?locale=en\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Prohibited business areas\n  text: The customer shall ensure that its offers are not included in the current list of restricted and prohibited\n    business activities.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: Only natural persons or legal entities, partnerships and non-profit organizations that are of legal age\n    and have unlimited legal\
  \ capacity can register.\n"
source_yaml_url: https://artifacts.apis.io/ablefy/eligibility/ablefy-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from ablefy's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Sales Platform
- Digital Products
- Online Courses
- Payments
- Checkout
- Membership
- Creator Economy
- E-Commerce
- Germany
- Webhook
---
