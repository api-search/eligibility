---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Interintellect is an international platform for intellectual, educational, and cultural events and community participation.
  entity_types:
  - text: The Service is intended for adults only. You must be at least 18 years old to create an account, purchase tickets or memberships, or otherwise use the Service.
    type: individual
  minimum_age:
    text: You must be at least 18 years old to create an account, purchase tickets or memberships, or otherwise use the Service.
    value: '18'
  restricted_uses:
  - summary: Most in-person events restricted to members
    text: Most in-person events are restricted to members. A small number of online events may also be restricted to members only.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: By using the Service, you represent and warrant that you are at least 18 years of age.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Interintellect
provenance_date: '2026-11-09'
provider_name: Interintellect
provider_slug: interintellect
slug: interintellect-eligibility
source_date: '2026-11-09'
source_filename: interintellect-eligibility.yml
source_heading: Eligibility
source_page: https://interintellect.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Interintellect\naid: interintellect\nurl: https://interintellect.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Interintellect is an international platform for intellectual, educational, and cultural events and community\n    participation.\nentity_types:\n- type: individual\n  text: The Service is intended for adults only. You must be at least 18 years old to create an account, purchase\n    tickets or memberships, or otherwise use the Service.\nrestricted_uses:\n- summary: Most in-person events restricted to members\n  text: Most in-person events are restricted\
  \ to members. A small number of online events may also be restricted\n    to members only.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: By using the Service, you represent and warrant that you are at least 18 years of age.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to create an account, purchase tickets or memberships, or otherwise use\n    the Service.\n"
source_yaml_url: https://artifacts.apis.io/interintellect/eligibility/interintellect-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Interintellect's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Community
- Event
- Salon
- Membership
- Intellectual
- Learning
- Culture
---
