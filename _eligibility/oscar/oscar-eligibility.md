---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You represent and warrant that you are not located in a country subject to a U.S. Government embargo
  entity_types:
  - text: You represent and warrant that you are an individual of legal age to form a binding contract.
    type: individual
  minimum_age:
    text: You represent and warrant that you are an individual of legal age to form a binding contract.
    value: legal age
  restricted_uses:
  - summary: Non-commercial personal use only
    text: You will only use the Services for your own internal, personal, non-commercial use
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You promise to provide us with accurate, complete, and updated registration information about yourself.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Oscar
provenance_date: '2026-11-10'
provider_name: Oscar
provider_slug: oscar
slug: oscar-eligibility
source_date: '2026-11-10'
source_filename: oscar-eligibility.yml
source_heading: Eligibility
source_page: https://www.hioscar.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Oscar\naid: oscar\nurl: https://www.hioscar.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You represent and warrant that you are not located in a country subject to a U.S. Government embargo\nentity_types:\n- type: individual\n  text: You represent and warrant that you are an individual of legal age to form a binding contract.\nrestricted_uses:\n- summary: Non-commercial personal use only\n  text: You will only use the Services for your own internal, personal, non-commercial use\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You promise to\
  \ provide us with accurate, complete, and updated registration information about yourself.\nminimum_age:\n  value: legal age\n  text: You represent and warrant that you are an individual of legal age to form a binding contract.\n"
source_yaml_url: https://artifacts.apis.io/oscar/eligibility/oscar-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Oscar's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Health Insurance
- Healthcare
- Insurance
- Health Tech
- Telehealth
- Medicare Advantage
- Digital Health
---
