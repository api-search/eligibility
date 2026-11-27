---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Services are controlled and operated from US-based facilities... You may not allow any individuals who are residents of a country embargoed by the United States to access or use the Services on your behalf
  entity_types:
  - text: you are at least 18 years old; or (b) you have and shall maintain permission of your Parent or Educational Institution to use the Services
    type: individual
  - text: 'If you open a User Account on behalf of an Educational Institution, company, organization or other entity, then: (i) “you” includes you and that entity'
    type: business
  minimum_age:
    text: you are at least 18 years old; or (b) you have and shall maintain permission of your Parent or Educational Institution to use the Services
    value: '18'
  restricted_uses:
  - summary: Commercial solicitation
    text: use the Services for any commercial solicitation purposes
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
name: Brisk Teaching
provenance_date: '2026-11-09'
provider_name: Brisk Teaching
provider_slug: brisk-teaching
slug: brisk-teaching-eligibility
source_date: '2026-11-09'
source_filename: brisk-teaching-eligibility.yml
source_heading: Eligibility
source_page: https://www.briskteaching.com/privacy/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Brisk Teaching\naid: brisk-teaching\nurl: https://www.briskteaching.com/privacy/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Services are controlled and operated from US-based facilities... You may not allow any individuals who\n    are residents of a country embargoed by the United States to access or use the Services on your behalf\nentity_types:\n- type: individual\n  text: you are at least 18 years old; or (b) you have and shall maintain permission of your Parent or Educational\n    Institution to use the Services\n- type: business\n  text: 'If you open a User Account\
  \ on behalf of an Educational Institution, company, organization or other entity,\n    then: (i) “you” includes you and that entity'\nrestricted_uses:\n- summary: Commercial solicitation\n  text: use the Services for any commercial solicitation purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you are at least 18 years old; or (b) you have and shall maintain permission of your Parent or Educational\n    Institution to use the Services\n"
source_yaml_url: https://artifacts.apis.io/brisk-teaching/eligibility/brisk-teaching-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Brisk Teaching's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Education
- EdTech
- K-12
- Teaching
- Software-as-a-Service
---
