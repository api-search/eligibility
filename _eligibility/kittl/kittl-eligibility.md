---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The User can use the Kittl Platform if he/she is a natural person who has reached the age of 18.
    type: individual
  - text: If the User uses the Kittl Platform on behalf of a company or organization, the User confirms to Kittl that he/she is authorized to act on behalf of that company or organization
    type: business
  minimum_age:
    text: a natural person who has reached the age of 18
    value: '18'
  restricted_uses:
  - summary: Activities that cause Kittl to violate law
    text: The User is prohibited from using the Kittl Platform to support activities that may cause Kittl to violate applicable law.
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
name: Kittl
provenance_date: '2026-11-09'
provider_name: Kittl
provider_slug: kittl
slug: kittl-eligibility
source_date: '2026-11-09'
source_filename: kittl-eligibility.yml
source_heading: Eligibility
source_page: https://www.kittl.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Kittl\naid: kittl\nurl: https://www.kittl.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The User can use the Kittl Platform if he/she is a natural person who has reached the age of 18.\n- type: business\n  text: If the User uses the Kittl Platform on behalf of a company or organization, the User confirms to Kittl that\n    he/she is authorized to act on behalf of that company or organization\nrestricted_uses:\n- summary: Activities that cause Kittl to violate law\n  text: The User is prohibited from using the Kittl Platform\
  \ to support activities that may cause Kittl to violate\n    applicable law.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: a natural person who has reached the age of 18\n"
source_yaml_url: https://artifacts.apis.io/kittl/eligibility/kittl-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Kittl's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Design
- Graphic Design
- Creative Tools
- SDK
- Developer Platform
- Extensions
- Print on Demand
- E-Commerce
- Artificial Intelligence
- Mockups
- Typography
---
