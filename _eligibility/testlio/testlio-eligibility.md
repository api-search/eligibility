---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are an individual, you represent and warrant that you have reached the age of majority in the jurisdiction in which you reside.
    type: individual
  - text: If you are an individual accessing or using the Site on behalf of, or for the benefit of, any corporation, partnership or other entity with which you are associated (an “ Organization ”), then you are agreeing to these ToU on behalf of yourself and such Organization
    type: business
  minimum_age:
    text: you represent and warrant that you have reached the age of majority in the jurisdiction in which you reside.
    value: age of majority
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
name: Testlio
provenance_date: '2026-11-10'
provider_name: Testlio
provider_slug: testlio
slug: testlio-eligibility
source_date: '2026-11-10'
source_filename: testlio-eligibility.yml
source_heading: Eligibility
source_page: https://www.testlio.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Testlio\naid: testlio\nurl: https://www.testlio.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: If you are an individual, you represent and warrant that you have reached the age of majority in the jurisdiction\n    in which you reside.\n- type: business\n  text: If you are an individual accessing or using the Site on behalf of, or for the benefit of, any corporation,\n    partnership or other entity with which you are associated (an “ Organization ”), then you are agreeing to these\n    ToU on behalf of yourself and such\
  \ Organization\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: age of majority\n  text: you represent and warrant that you have reached the age of majority in the jurisdiction in which you reside.\n"
source_yaml_url: https://artifacts.apis.io/testlio/eligibility/testlio-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from Testlio's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Testing
- Quality Assurance
- QA
- Software Testing
- Crowdsourced Testing
- Test Automation
- Mobile App Testing
- DevOps
---
