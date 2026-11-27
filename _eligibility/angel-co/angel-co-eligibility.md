---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Wellfound makes no representation that the Site and Services are appropriate or available in other locations.
  entity_types:
  - text: 'Candidates: Users that access the Site through the account of a potential employee or contractor.'
    type: individual
  - text: 'Employers: Users that access the Site through the account of a potential employer'
    type: business
  minimum_age:
    text: You are at least 16 years old
    value: '16'
  restricted_uses:
  - summary: Commercial or competing use of content
    text: use any Content, or other information acquired from the Site or through your use of the Services for commercial activity or in a manner that directly or indirectly competes with Wellfound
  verification:
    approval_required: null
    kyb: null
    kyc: false
    text: Wellfound does not inquire into the backgrounds of its Users or attempt to verify the Content provided by its Users
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: AngelList
provenance_date: '2026-11-09'
provider_name: AngelList
provider_slug: angel-co
slug: angel-co-eligibility
source_date: '2026-11-09'
source_filename: angel-co-eligibility.yml
source_heading: Eligibility
source_page: https://wellfound.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AngelList\naid: angel-co\nurl: https://wellfound.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Wellfound makes no representation that the Site and Services are appropriate or available in other locations.\nentity_types:\n- type: individual\n  text: 'Candidates: Users that access the Site through the account of a potential employee or contractor.'\n- type: business\n  text: 'Employers: Users that access the Site through the account of a potential employer'\nrestricted_uses:\n- summary: Commercial or competing use of content\n  text: use any Content, or other information\
  \ acquired from the Site or through your use of the Services for commercial\n    activity or in a manner that directly or indirectly competes with Wellfound\nverification:\n  kyc: false\n  kyb: null\n  approval_required: null\n  text: Wellfound does not inquire into the backgrounds of its Users or attempt to verify the Content provided by\n    its Users\nminimum_age:\n  value: '16'\n  text: You are at least 16 years old\n"
source_yaml_url: https://artifacts.apis.io/angel-co/eligibility/angel-co-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from AngelList's own page on 2026-11-09.
synthetic: false
tags:
- Startups
- Recruiting
- Job Board
- Venture Capital
- Platform
---
