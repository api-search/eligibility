---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 'Users must fulfil the following requirements to be able to register: Age of majority, at least 18 years of age'
    type: individual
  minimum_age:
    text: Age of majority, at least 18 years of age
    value: '18'
  restricted_uses:
  - summary: Registrant must act in own name and economic interest
    text: Acting under one's own name and in one's own economic interest and not at the instigation of a third party or acting as an authorised representative of a legal person/partnership
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Invesdor INV AG has the right to refuse a registration in individual cases.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Invesdor
provenance_date: '2026-11-09'
provider_name: Invesdor
provider_slug: invesdor
slug: invesdor-eligibility
source_date: '2026-11-09'
source_filename: invesdor-eligibility.yml
source_heading: Eligibility
source_page: https://www.invesdor.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Invesdor\naid: invesdor\nurl: https://www.invesdor.com/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: 'Users must fulfil the following requirements to be able to register: Age of majority, at least 18 years\n    of age'\nrestricted_uses:\n- summary: Registrant must act in own name and economic interest\n  text: Acting under one's own name and in one's own economic interest and not at the instigation of a third party\n    or acting as an authorised representative of a legal person/partnership\nverification:\n \
  \ kyc: null\n  kyb: null\n  approval_required: true\n  text: Invesdor INV AG has the right to refuse a registration in individual cases.\nminimum_age:\n  value: '18'\n  text: Age of majority, at least 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/invesdor/eligibility/invesdor-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Invesdor's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Crowdfunding
- Investment
- Fintech
- Crowdinvesting
- Capital Markets
- Renewable Energy
- Europe
---
