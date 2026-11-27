---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Use of this Site is unauthorized in any jurisdiction that does not give effect to all provisions of these terms and conditions
  entity_types:
  - text: You are not authorized to use this Site unless you are at least 19 years of age and able to enter into legally binding contracts.
    type: individual
  minimum_age:
    text: You are not authorized to use this Site unless you are at least 19 years of age and able to enter into legally binding contracts.
    value: '19'
  restricted_uses:
  - summary: unlawful use
    text: you warrant that you will not use this website for any purpose that is unlawful or prohibited by these terms, conditions, and notices.
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
name: Sonder
provenance_date: '2026-11-10'
provider_name: Sonder
provider_slug: sonder
slug: sonder-eligibility
source_date: '2026-11-10'
source_filename: sonder-eligibility.yml
source_heading: Eligibility
source_page: https://sonder.com/site-terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Sonder\naid: sonder\nurl: https://sonder.com/site-terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Use of this Site is unauthorized in any jurisdiction that does not give effect to all provisions of these\n    terms and conditions\nentity_types:\n- type: individual\n  text: You are not authorized to use this Site unless you are at least 19 years of age and able to enter into legally\n    binding contracts.\nrestricted_uses:\n- summary: unlawful use\n  text: you warrant that you will not use this website for any purpose that is unlawful or prohibited by these terms,\n    conditions,\
  \ and notices.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '19'\n  text: You are not authorized to use this Site unless you are at least 19 years of age and able to enter into legally\n    binding contracts.\n"
source_yaml_url: https://artifacts.apis.io/sonder/eligibility/sonder-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Sonder's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Consumer
- Hospitality
- Travel
- Lodging
- Short-Term Rental
- Accommodation
---
