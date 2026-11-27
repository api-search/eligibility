---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: you are not located in a country that is subject to a U.S. Government embargo, or that has been designated by the U.S. Government as a terrorist-supporting country
  entity_types:
  - text: You may use the Services only if you are 18 years or older and capable of forming a binding contract with Known
    type: individual
  minimum_age:
    text: You may use the Services only if you are 18 years or older
    value: '18'
  restricted_uses:
  - summary: Commercial purposes
    text: Use the Services, or any portion thereof, for any commercial purpose or for the benefit of any third party
  verification:
    approval_required: null
    kyb: null
    kyc: false
    text: Known does not conduct criminal background checks, screening, or verification of the identity, criminal history, health, physical condition or other background information of its users.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Known
provenance_date: '2026-11-09'
provider_name: Known
provider_slug: knowndating-com
slug: knowndating-com-eligibility
source_date: '2026-11-09'
source_filename: knowndating-com-eligibility.yml
source_heading: Eligibility
source_page: https://known.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Known\naid: knowndating-com\nurl: https://known.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: you are not located in a country that is subject to a U.S. Government embargo, or that has been designated\n    by the U.S. Government as a terrorist-supporting country\nentity_types:\n- type: individual\n  text: You may use the Services only if you are 18 years or older and capable of forming a binding contract with\n    Known\nrestricted_uses:\n- summary: Commercial purposes\n  text: Use the Services, or any portion thereof, for any commercial purpose or for the benefit of\
  \ any third party\nverification:\n  kyc: false\n  kyb: null\n  approval_required: null\n  text: Known does not conduct criminal background checks, screening, or verification of the identity, criminal\n    history, health, physical condition or other background information of its users.\nminimum_age:\n  value: '18'\n  text: You may use the Services only if you are 18 years or older\n"
source_yaml_url: https://artifacts.apis.io/knowndating-com/eligibility/knowndating-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Known's own page on 2026-11-09.
synthetic: false
tags:
- Company
---
