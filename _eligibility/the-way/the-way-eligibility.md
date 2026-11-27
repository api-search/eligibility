---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: 'Users from New Jersey and California are referenced; the page names no general country restriction. Also: you represent you are not located in a country subject to a U.S. Government embargo.'
  minimum_age:
    text: If you are under 13 years of age, you are not authorized to use the Service, with or without registering.
    value: '13'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You may be required to register with Company or provide information about yourself (e.g., name and email address) in order to access and use certain features of the Service.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: The Way
provenance_date: '2026-11-10'
provider_name: The Way
provider_slug: the-way
slug: the-way-eligibility
source_date: '2026-11-10'
source_filename: the-way-eligibility.yml
source_heading: Eligibility
source_page: https://www.thewayapp.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: The Way\naid: the-way\nurl: https://www.thewayapp.com/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: 'Users from New Jersey and California are referenced; the page names no general country restriction. Also:\n    you represent you are not located in a country subject to a U.S. Government embargo.'\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You may be required to register with Company or provide information about yourself (e.g., name and email\n    address) in order to access and use certain\
  \ features of the Service.\nminimum_age:\n  value: '13'\n  text: If you are under 13 years of age, you are not authorized to use the Service, with or without registering.\n"
source_yaml_url: https://artifacts.apis.io/the-way/eligibility/the-way-eligibility.yml
stated_fields:
- countries
- verification
- minimum_age
summary_line: 3 quoted statements, read from The Way's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Meditation
- Wellness
- Zen
- Spirituality
- Mental Health
---
