---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You represent and warrant that you are an individual of legal age to form a binding contract
    type: individual
  minimum_age:
    text: if you are a child under 13 years of age, please do not attempt to register for or otherwise use the Services
    value: '13'
  restricted_uses:
  - summary: Non-commercial use only
    text: You will only use the Services for your own internal, personal, non-commercial use
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You may be required to sign up for an account, select a password and user name
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Realm
provenance_date: '2026-11-10'
provider_name: Realm
provider_slug: realm
slug: realm-eligibility
source_date: '2026-11-10'
source_filename: realm-eligibility.yml
source_heading: Eligibility
source_page: https://realmhome.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Realm\naid: realm\nurl: https://realmhome.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You represent and warrant that you are an individual of legal age to form a binding contract\nrestricted_uses:\n- summary: Non-commercial use only\n  text: You will only use the Services for your own internal, personal, non-commercial use\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You may be required to sign up for an account, select a password and user name\nminimum_age:\n  value: '13'\n  text: if you\
  \ are a child under 13 years of age, please do not attempt to register for or otherwise use the Services\n"
source_yaml_url: https://artifacts.apis.io/realm/eligibility/realm-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Realm's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Real Estate
- Property Data
- Home Improvement
- Home Valuation
- PropTech
- Consumer
---
