---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Bloomberg makes no representation that materials in this site are appropriate or available for use in other locations.
  entity_types:
  - text: you are at least eighteen (18) years old
    type: individual
  minimum_age:
    text: you are at least eighteen (18) years old
    value: '18'
  restricted_uses:
  - summary: Illegal purposes
    text: You may not use the Service for any illegal purpose, for the facilitation of the violation of any law or regulation, or in any manner inconsistent with the TOS.
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
name: Bloomberg Message
provenance_date: '2026-11-09'
provider_name: Bloomberg Message
provider_slug: bloomberg-message
slug: bloomberg-message-eligibility
source_date: '2026-11-09'
source_filename: bloomberg-message-eligibility.yml
source_heading: Eligibility
source_page: https://www.bloomberg.com/notices/tos/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bloomberg Message\naid: bloomberg-message\nurl: https://www.bloomberg.com/notices/tos/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: Bloomberg makes no representation that materials in this site are appropriate or available for use in other\n    locations.\nentity_types:\n- type: individual\n  text: you are at least eighteen (18) years old\nrestricted_uses:\n- summary: Illegal purposes\n  text: You may not use the Service for any illegal purpose, for the facilitation of the violation of any law or\n    regulation, or in any manner inconsistent with the TOS.\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you are at least eighteen (18) years old\n"
source_yaml_url: https://artifacts.apis.io/bloomberg-message/eligibility/bloomberg-message-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Bloomberg Message's own page on 2026-11-09.
synthetic: false
tags:
- Messaging
- Financial Communication
- Bloomberg IB
- Compliance
- Trading Communication
- Bloomberg
---
