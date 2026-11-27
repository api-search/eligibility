---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    - CA
    text: Unless otherwise explicitly stated, all materials found on the Service are solely directed to individuals, companies, or other entities located in the United States and Canada. You may not use the Service if you are a resident of a country embargoed by the United States
  entity_types:
  - text: You must be at least 13 years of age to create a PlayVS Account directly (without a Parent Account) and use the Service
    type: individual
  - text: IF YOU OPEN A PLAYVS ACCOUNT ON BEHALF OF A SCHOOL, ORGANIZATION, OR OTHER ENTITY, THEN (I) “YOU” INCLUDES YOU AND THAT ENTITY
    type: other
  minimum_age:
    text: You must be at least 13 years of age to create a PlayVS Account directly (without a Parent Account) and use the Service
    value: '13'
  restricted_uses:
  - summary: Embargoed countries and blocked persons
    text: You may not use the Service if you are a resident of a country embargoed by the United States, or are a foreign person or entity blocked or denied by the United States government.
  - summary: Non-commercial use only
    text: for your personal, noncommercial use only
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
name: Play Versus
provenance_date: '2026-11-10'
provider_name: Play Versus
provider_slug: play-versus
slug: play-versus-eligibility
source_date: '2026-11-10'
source_filename: play-versus-eligibility.yml
source_heading: Eligibility
source_page: https://playvs.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Play Versus\naid: play-versus\nurl: https://playvs.com/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  - CA\n  excluded: []\n  text: Unless otherwise explicitly stated, all materials found on the Service are solely directed to individuals,\n    companies, or other entities located in the United States and Canada. You may not use the Service if you are\n    a resident of a country embargoed by the United States\nentity_types:\n- type: individual\n  text: You must be at least 13 years of age to create a PlayVS Account directly (without a Parent Account) and\n    use the Service\n\
  - type: other\n  text: IF YOU OPEN A PLAYVS ACCOUNT ON BEHALF OF A SCHOOL, ORGANIZATION, OR OTHER ENTITY, THEN (I) “YOU” INCLUDES\n    YOU AND THAT ENTITY\nrestricted_uses:\n- summary: Embargoed countries and blocked persons\n  text: You may not use the Service if you are a resident of a country embargoed by the United States, or are a\n    foreign person or entity blocked or denied by the United States government.\n- summary: Non-commercial use only\n  text: for your personal, noncommercial use only\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You must be at least 13 years of age to create a PlayVS Account directly (without a Parent Account) and\n    use the Service\n"
source_yaml_url: https://artifacts.apis.io/play-versus/eligibility/play-versus-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from Play Versus's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Esports
- Gaming
- Education
- Scholastic
- Competitions
- EdTech
---
