---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: you are not located in a country that is subject to a U.S. Government embargo, or that has been designated by the U.S. Government as a terrorist-supporting country
  entity_types:
  - text: You may use the Services only if you are 16 years or older and capable of forming a binding contract with Albert or a partner of Albert
    type: individual
  - text: If you are accessing the Albert Platform as an Authorized User pursuant to an Albert Software Subscription Agreement executed by your organization
    type: business
  minimum_age:
    text: You may use the Services only if you are 16 years or older
    value: '16'
  restricted_uses:
  - summary: Personal, non-commercial App use only
    text: to run the App solely for your own personal non-commercial purposes
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
name: Albert
provenance_date: '2026-11-09'
provider_name: Albert
provider_slug: albert
slug: albert-eligibility
source_date: '2026-11-09'
source_filename: albert-eligibility.yml
source_heading: Eligibility
source_page: https://www.albertinvent.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Albert\naid: albert\nurl: https://www.albertinvent.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: you are not located in a country that is subject to a U.S. Government embargo, or that has been designated\n    by the U.S. Government as a terrorist-supporting country\nentity_types:\n- type: individual\n  text: You may use the Services only if you are 16 years or older and capable of forming a binding contract with\n    Albert or a partner of Albert\n- type: business\n  text: If you are accessing the Albert Platform as an Authorized User pursuant to an Albert\
  \ Software Subscription\n    Agreement executed by your organization\nrestricted_uses:\n- summary: Personal, non-commercial App use only\n  text: to run the App solely for your own personal non-commercial purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: You may use the Services only if you are 16 years or older\n"
source_yaml_url: https://artifacts.apis.io/albert/eligibility/albert-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Albert's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Chemistry
- Materials Science
- R&D
- Electronic Lab Notebook
- Machine Learning
- Life Sciences
- Formulation
---
