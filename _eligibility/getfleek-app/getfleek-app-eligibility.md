---
api_specs:
- filename: getfleek-app-openapi-generated.yml
  format: yaml
  label: getfleek-app API
  slug: getfleek-app-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/getfleek-app/openapi/_ae-authored/getfleek-app-openapi-generated.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: 'Spin the Wheel contest: You should be an Individual legal resident of India. Some products not available in all geographic areas.'
  minimum_age:
    text: You are 18 years of age or older
    value: '18'
  restricted_uses:
  - summary: No commercial use
    text: This Promotion is offered for your personal use and not for commercial use and youagree not to sell any rewards redeemed through this Promotion.
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
name: getfleek-app
provenance_date: '2026-11-09'
provider_name: getfleek-app
provider_slug: getfleek-app
slug: getfleek-app-eligibility
source_date: '2026-11-09'
source_filename: getfleek-app-eligibility.yml
source_heading: Eligibility
source_page: https://getfleek.app/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: getfleek-app\naid: getfleek-app\nurl: https://getfleek.app/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: 'Spin the Wheel contest: You should be an Individual legal resident of India. Some products not available\n    in all geographic areas.'\nentity_types: []\nrestricted_uses:\n- summary: No commercial use\n  text: This Promotion is offered for your personal use and not for commercial use and youagree not to sell any\n    rewards redeemed through this Promotion.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: '18'\n  text: You are 18 years of age or older\n"
source_yaml_url: https://artifacts.apis.io/getfleek-app/eligibility/getfleek-app-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from getfleek-app's own page on 2026-11-09.
synthetic: false
tags:
- Subscription
- Rewards
- Fintech
- Consumer App
- Platform
---
