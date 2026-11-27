---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - AE
    text: This Section 7.9 applies exclusively to customers who receive subscription plan deliveries in the United Arab Emirates
  entity_types:
  - text: You acknowledge that you have full legal capacity and are at least eighteen (18) years of age.
    type: individual
  minimum_age:
    text: You acknowledge that you have full legal capacity and are at least eighteen (18) years of age.
    value: '18'
  restricted_uses:
  - summary: Lawful use only
    text: The App may only be used for lawful purposes in accordance with the terms of the license granted in these Terms & Conditions.
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
name: Calo
provenance_date: '2026-11-09'
provider_name: Calo
provider_slug: calo
slug: calo-eligibility
source_date: '2026-11-09'
source_filename: calo-eligibility.yml
source_heading: Eligibility
source_page: https://calo.app/en/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Calo\naid: calo\nurl: https://calo.app/en/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - AE\n  excluded: []\n  text: This Section 7.9 applies exclusively to customers who receive subscription plan deliveries in the United\n    Arab Emirates\nentity_types:\n- type: individual\n  text: You acknowledge that you have full legal capacity and are at least eighteen (18) years of age.\nrestricted_uses:\n- summary: Lawful use only\n  text: The App may only be used for lawful purposes in accordance with the terms of the license granted in these\n    Terms & Conditions.\nverification:\n  kyc:\
  \ null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You acknowledge that you have full legal capacity and are at least eighteen (18) years of age.\n"
source_yaml_url: https://artifacts.apis.io/calo/eligibility/calo-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Calo's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Food
- Meal Delivery
- Meal Plans
- Nutrition
- Health
- Subscription
- Food Tech
---
