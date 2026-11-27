---
claim_count: 5
description: ''
doc:
  countries:
    excluded:
    - CU
    - KP
    - IR
    - SD
    - SY
    served: []
    text: 'You will not use the Services to directly or indirectly conduct, promote, or facilitate business in countries and/or with nationals or members of governments that are subject to U.S. embargoes or trade sanctions (these embargoed and sanctioned countries are: Cuba, North Korea, Iran, Sudan, and Syria)'
  entity_types:
  - text: THE SERVICES PROVIDED PURSUANT TO THESE TERMS ARE INTENDED FOR BUSINESS CUSTOMERS ONLY.
    type: business
  - text: if You are an individual, You are 18 years old or older
    type: individual
  minimum_age:
    text: if You are an individual, You are 18 years old or older
    value: '18'
  restricted_uses:
  - summary: adult or sexually explicit content
    text: collects, transmits, or stores any type of adult, mature, or sexually explicit content.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- CU
- KP
- IR
- SD
- SY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Luminate *
provenance_date: '2026-11-10'
provider_name: Luminate *
provider_slug: luminate-com
slug: luminate-com-eligibility
source_date: '2026-11-10'
source_filename: luminate-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.turbify.com/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Luminate *\naid: luminate-com\nurl: https://www.turbify.com/tos\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded:\n  - CU\n  - KP\n  - IR\n  - SD\n  - SY\n  text: 'You will not use the Services to directly or indirectly conduct, promote, or facilitate business in countries\n    and/or with nationals or members of governments that are subject to U.S. embargoes or trade sanctions (these\n    embargoed and sanctioned countries are: Cuba, North Korea, Iran, Sudan, and Syria)'\nentity_types:\n- type: business\n  text: THE SERVICES PROVIDED PURSUANT TO THESE TERMS ARE INTENDED FOR\
  \ BUSINESS CUSTOMERS ONLY.\n- type: individual\n  text: if You are an individual, You are 18 years old or older\nrestricted_uses:\n- summary: adult or sexually explicit content\n  text: collects, transmits, or stores any type of adult, mature, or sexually explicit content.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: if You are an individual, You are 18 years old or older\n"
source_yaml_url: https://artifacts.apis.io/luminate-com/eligibility/luminate-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Luminate *'s own page on 2026-11-10.
synthetic: false
tags:
- Company
---
