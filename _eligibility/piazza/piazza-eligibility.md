---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Those who access or use the Service from other jurisdictions do so at their own volition and are entirely responsible for compliance with all applicable United States and local laws and regulations. You may not use the Service if you are a resident of a country embargoed by the United States
  entity_types:
  - text: You represent that you are over the age of thirteen (13) years old in the United States, sixteen (16) years old in the European Union, or fourteen (14) years old if you live in Spain or South Korea
    type: individual
  minimum_age:
    text: You represent that you are over the age of thirteen (13) years old in the United States, sixteen (16) years old in the European Union, or fourteen (14) years old if you live in Spain or South Korea
    value: 13 (US), 16 (EU), 14 (Spain, South Korea)
  restricted_uses:
  - summary: Illegal or prohibited conduct
    text: 'You may not use the Service to and you represent and warrant that any User Content (as defined below) that you post does not: violate any law or to promote any illegal activities'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: YOU UNDERSTAND THAT PIAZZA DOES NOT MAKE ANY ATTEMPT TO VERIFY THE STATEMENTS OF USERS OF THE SERVICE.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Piazza
provenance_date: '2026-11-10'
provider_name: Piazza
provider_slug: piazza
slug: piazza-eligibility
source_date: '2026-11-10'
source_filename: piazza-eligibility.yml
source_heading: Eligibility
source_page: https://piazza.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Piazza\naid: piazza\nurl: https://piazza.com/legal/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Those who access or use the Service from other jurisdictions do so at their own volition and are entirely\n    responsible for compliance with all applicable United States and local laws and regulations. You may not use\n    the Service if you are a resident of a country embargoed by the United States\nentity_types:\n- type: individual\n  text: You represent that you are over the age of thirteen (13) years old in the United States, sixteen (16) years\n    old in the European Union,\
  \ or fourteen (14) years old if you live in Spain or South Korea\nrestricted_uses:\n- summary: Illegal or prohibited conduct\n  text: 'You may not use the Service to and you represent and warrant that any User Content (as defined below) that\n    you post does not: violate any law or to promote any illegal activities'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: YOU UNDERSTAND THAT PIAZZA DOES NOT MAKE ANY ATTEMPT TO VERIFY THE STATEMENTS OF USERS OF THE SERVICE.\nminimum_age:\n  value: 13 (US), 16 (EU), 14 (Spain, South Korea)\n  text: You represent that you are over the age of thirteen (13) years old in the United States, sixteen (16) years\n    old in the European Union, or fourteen (14) years old if you live in Spain or South Korea\n"
source_yaml_url: https://artifacts.apis.io/piazza/eligibility/piazza-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Piazza's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Consumer
- Education
- EdTech
- Q&A
- Collaboration
- LMS
- Higher Education
- LTI
---
