---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 'you must be a REAL human (because feelings matter): who is at least 13 years old.'
    type: individual
  - text: who has the legal authority to create an account on behalf of another person, a company, an organisation, a government or another legal entity, if you are not creating an account for yourself.
    type: business
  minimum_age:
    text: who is at least 13 years old.
    value: '13'
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
name: BeReal
provenance_date: '2026-11-09'
provider_name: BeReal
provider_slug: bere-al
slug: bere-al-eligibility
source_date: '2026-11-09'
source_filename: bere-al-eligibility.yml
source_heading: Eligibility
source_page: https://bereal.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BeReal\naid: bere-al\nurl: https://bereal.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: 'you must be a REAL human (because feelings matter): who is at least 13 years old.'\n- type: business\n  text: who has the legal authority to create an account on behalf of another person, a company, an organisation,\n    a government or another legal entity, if you are not creating an account for yourself.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n\
  \  text: who is at least 13 years old.\n"
source_yaml_url: https://artifacts.apis.io/bere-al/eligibility/bere-al-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from BeReal's own page on 2026-11-09.
synthetic: false
tags:
- Company
---
