---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: If we are not able to service your geographic area with our Service, you will be notified when creating an account.
  entity_types:
  - text: You must be the age of majority in your jurisdiction and capable of entering into binding contracts
    type: individual
  minimum_age:
    text: You must be the age of majority in your jurisdiction and capable of entering into binding contracts
    value: age of majority
  restricted_uses:
  - summary: Unlawful purposes
    text: You will not use the Website or the Platform for any unlawful purpose
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: We are under no obligation to accept any individual as a Subscriber and may accept or reject any registration in our sole and complete discretion
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Gobble
provenance_date: '2026-11-09'
provider_name: Gobble
provider_slug: gobble
slug: gobble-eligibility
source_date: '2026-11-09'
source_filename: gobble-eligibility.yml
source_heading: Eligibility
source_page: https://www.gobble.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Gobble\naid: gobble\nurl: https://www.gobble.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: If we are not able to service your geographic area with our Service, you will be notified when creating\n    an account.\nentity_types:\n- type: individual\n  text: You must be the age of majority in your jurisdiction and capable of entering into binding contracts\nrestricted_uses:\n- summary: Unlawful purposes\n  text: You will not use the Website or the Platform for any unlawful purpose\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: We are under\
  \ no obligation to accept any individual as a Subscriber and may accept or reject any registration\n    in our sole and complete discretion\nminimum_age:\n  value: age of majority\n  text: You must be the age of majority in your jurisdiction and capable of entering into binding contracts\n"
source_yaml_url: https://artifacts.apis.io/gobble/eligibility/gobble-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Gobble's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Meal Kit
- Food Delivery
- Subscription
- Direct to Consumer
- Consumer
- E-Commerce
---
