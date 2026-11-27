---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: No served or excluded countries are named, except a user representation that they are not located in a country subject to a U.S. Government embargo (Apple App Store section).
  entity_types:
  - text: 'The Services are available only to individuals who: (a) are at least sixteen (16) years old; and (b) possess the legal capacity to enter into these Terms'
    type: individual
  - text: You agree to be bound by these Terms on your own behalf and, where applicable, on behalf of your organization
    type: business
  minimum_age:
    text: at least sixteen (16) years old
    value: '16'
  restricted_uses:
  - summary: Illegal or unauthorized use
    text: (a) use the Services for any illegal, immoral, unlawful and/or unauthorized purpose;
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
name: Boards
provenance_date: '2026-11-09'
provider_name: Boards
provider_slug: boards
slug: boards-eligibility
source_date: '2026-11-09'
source_filename: boards-eligibility.yml
source_heading: Eligibility
source_page: https://www.boards.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Boards\naid: boards\nurl: https://www.boards.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: No served or excluded countries are named, except a user representation that they are not located in a country\n    subject to a U.S. Government embargo (Apple App Store section).\nentity_types:\n- type: individual\n  text: 'The Services are available only to individuals who: (a) are at least sixteen (16) years old; and (b) possess\n    the legal capacity to enter into these Terms'\n- type: business\n  text: You agree to be bound by these Terms on your own behalf\
  \ and, where applicable, on behalf of your organization\nrestricted_uses:\n- summary: Illegal or unauthorized use\n  text: (a) use the Services for any illegal, immoral, unlawful and/or unauthorized purpose;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: at least sixteen (16) years old\n"
source_yaml_url: https://artifacts.apis.io/boards/eligibility/boards-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Boards's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer
- Network Marketing
- Direct Sales
- Collaboration
- Team Enablement
- Mobile App
- Software-as-a-Service
---
