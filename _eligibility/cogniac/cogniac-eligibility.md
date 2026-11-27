---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Company Properties are controlled and offered by Company from its facilities in the United States of America. Company makes no representations that Company Properties are appropriate or available for use in other locations.
  entity_types:
  - text: THE TERM “YOU” REFERS TO THE INDIVIDUAL OR LEGAL ENTITY, AS APPLICABLE, IDENTIFIED AS THE USER WHEN YOU REGISTERED ON THE WEBSITE.
    type: business
  minimum_age:
    text: You represent that you are (1) at least thirteen (13) years old
    value: '13'
  restricted_uses:
  - summary: Export control and prohibited weapons uses
    text: You also will not use Company Properties for any purpose prohibited by U.S. law, including the development, design, manufacture or production of missiles, nuclear, chemical or biological weapons.
  - summary: Sanctioned countries and parties
    text: you are not located in a country that is subject to a U.S. Government embargo
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
name: Cogniac
provenance_date: '2026-11-09'
provider_name: Cogniac
provider_slug: cogniac
slug: cogniac-eligibility
source_date: '2026-11-09'
source_filename: cogniac-eligibility.yml
source_heading: Eligibility
source_page: https://cogniac.ai/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cogniac\naid: cogniac\nurl: https://cogniac.ai/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Company Properties are controlled and offered by Company from its facilities in the United States of America.\n    Company makes no representations that Company Properties are appropriate or available for use in other locations.\nentity_types:\n- type: business\n  text: THE TERM “YOU” REFERS TO THE INDIVIDUAL OR LEGAL ENTITY, AS APPLICABLE, IDENTIFIED AS THE USER WHEN YOU\n    REGISTERED ON THE WEBSITE.\nrestricted_uses:\n- summary: Export control and prohibited weapons\
  \ uses\n  text: You also will not use Company Properties for any purpose prohibited by U.S. law, including the development,\n    design, manufacture or production of missiles, nuclear, chemical or biological weapons.\n- summary: Sanctioned countries and parties\n  text: you are not located in a country that is subject to a U.S. Government embargo\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You represent that you are (1) at least thirteen (13) years old\n"
source_yaml_url: https://artifacts.apis.io/cogniac/eligibility/cogniac-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Cogniac's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Computer Vision
- Artificial Intelligence
- Machine Learning
- Visual Inspection
- Defect Detection
- Edge AI
- Manufacturing
- Industrial IoT
- MLOps
---
