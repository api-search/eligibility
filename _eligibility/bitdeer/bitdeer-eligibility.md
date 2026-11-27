---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: THE SERVICES PROVIDED BY BITDEER ARE NOT AVAILABLE TO THE FOLLOWING
  entity_types:
  - text: 'if you are a natural person: you are at least 18 years old of age and have full civil capacity'
    type: individual
  - text: 'if you are an entity: you are duly organized and validly existing under the laws of the jurisdiction of your organization or incorporation'
    type: business
  minimum_age:
    text: you are at least 18 years old of age and have full civil capacity
    value: '18'
  restricted_uses:
  - summary: Sanctions violations
    text: 'YOU SHALL NOT USE THE SERVICES: 1) IN VIOLATION OF ANY SANCTIONS LAWS'
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: For compliance purpose such as KYC (know your customer) and/or anti-money laundering, Bitdeer reserves the right to request you to provide Bitdeer your PII
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: BitDeer
provenance_date: '2026-11-09'
provider_name: BitDeer
provider_slug: bitdeer
slug: bitdeer-eligibility
source_date: '2026-11-09'
source_filename: bitdeer-eligibility.yml
source_heading: Eligibility
source_page: https://www.bitdeer.com/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BitDeer\naid: bitdeer\nurl: https://www.bitdeer.com/terms-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: THE SERVICES PROVIDED BY BITDEER ARE NOT AVAILABLE TO THE FOLLOWING\nentity_types:\n- type: individual\n  text: 'if you are a natural person: you are at least 18 years old of age and have full civil capacity'\n- type: business\n  text: 'if you are an entity: you are duly organized and validly existing under the laws of the jurisdiction of\n    your organization or incorporation'\nrestricted_uses:\n- summary: Sanctions violations\n  text: 'YOU SHALL NOT USE THE SERVICES:\
  \ 1) IN VIOLATION OF ANY SANCTIONS LAWS'\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: For compliance purpose such as KYC (know your customer) and/or anti-money laundering, Bitdeer reserves the\n    right to request you to provide Bitdeer your PII\nminimum_age:\n  value: '18'\n  text: you are at least 18 years old of age and have full civil capacity\n"
source_yaml_url: https://artifacts.apis.io/bitdeer/eligibility/bitdeer-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from BitDeer's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Cloud
- HPC
- Bitcoin
- Mining
---
