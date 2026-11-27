---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Platform is available only to persons (i) who are eighteen (18) years or older
    type: individual
  minimum_age:
    text: YOU MUST BE AT LEAST THIRTEEN (13) YEARS TO ACCESS AND USE THE PLATFORM
    value: '13'
  restricted_uses:
  - summary: Unlawful use
    text: Use the Platform for any purpose in violation of applicable local, state, national, or international law.
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
name: Blank Street
provenance_date: '2026-11-09'
provider_name: Blank Street
provider_slug: blank-street
slug: blank-street-eligibility
source_date: '2026-11-09'
source_filename: blank-street-eligibility.yml
source_heading: Eligibility
source_page: https://www.blankstreet.com/en-US/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Blank Street\naid: blank-street\nurl: https://www.blankstreet.com/en-US/tos\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Platform is available only to persons (i) who are eighteen (18) years or older\nrestricted_uses:\n- summary: Unlawful use\n  text: Use the Platform for any purpose in violation of applicable local, state, national, or international law.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: YOU MUST BE AT LEAST THIRTEEN (13)\
  \ YEARS TO ACCESS AND USE THE PLATFORM\n"
source_yaml_url: https://artifacts.apis.io/blank-street/eligibility/blank-street-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Blank Street's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer
- Coffee
- Retail
- Food and Beverage
- Loyalty
- Mobile Ordering
---
