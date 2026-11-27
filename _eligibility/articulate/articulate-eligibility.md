---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Customer shall not permit Users to access or use the Services in a U.S. embargoed country or in violation of any U.S. export law or regulation.
  entity_types:
  - text: the customer, organization, or individual accessing, purchasing, or using the Services
    type: individual
  - text: If you access or use the Services on behalf of a company, employer, school, agency, or other organization, you represent that you have authority to bind that organization
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Academic Version eligibility
    text: Customer may only use the Academic Version if Customer meets Articulate’s eligibility requirements.
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
name: Articulate
provenance_date: '2026-11-09'
provider_name: Articulate
provider_slug: articulate
slug: articulate-eligibility
source_date: '2026-11-09'
source_filename: articulate-eligibility.yml
source_heading: Eligibility
source_page: https://www.articulate.com/360-terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Articulate\naid: articulate\nurl: https://www.articulate.com/360-terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Customer shall not permit Users to access or use the Services in a U.S. embargoed country or in violation\n    of any U.S. export law or regulation.\nentity_types:\n- type: individual\n  text: the customer, organization, or individual accessing, purchasing, or using the Services\n- type: business\n  text: If you access or use the Services on behalf of a company, employer, school, agency, or other organization,\n    you represent that you have authority\
  \ to bind that organization\nrestricted_uses:\n- summary: Academic Version eligibility\n  text: Customer may only use the Academic Version if Customer meets Articulate’s eligibility requirements.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/articulate/eligibility/articulate-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from Articulate's own page on 2026-11-09.
synthetic: false
tags:
- Company
- EdTech
- E-Learning
- LMS
- Training
- Course Authoring
- SSO
---
