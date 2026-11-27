---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old to use the Services.
    type: individual
  minimum_age:
    text: You must be at least 18 years old to use the Services.
    value: '18'
  restricted_uses:
  - summary: Embargoed countries
    text: You represent and warrant that you are not located in a country subject to a U.S. Government embargo
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Wag! itself does not conduct background checks and does not independently verify information in the background checks.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Wag!
provenance_date: '2026-11-10'
provider_name: Wag!
provider_slug: wag
slug: wag-eligibility
source_date: '2026-11-10'
source_filename: wag-eligibility.yml
source_heading: Eligibility
source_page: https://safety.wagwalking.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Wag!\naid: wag\nurl: https://safety.wagwalking.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old to use the Services.\nrestricted_uses:\n- summary: Embargoed countries\n  text: You represent and warrant that you are not located in a country subject to a U.S. Government embargo\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Wag! itself does not conduct background checks and does not independently verify information in the background\n    checks.\n\
  minimum_age:\n  value: '18'\n  text: You must be at least 18 years old to use the Services.\n"
source_yaml_url: https://artifacts.apis.io/wag/eligibility/wag-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Wag!'s own page on 2026-11-10.
synthetic: false
tags:
- Company
- Pet Care
- Dog Walking
- Marketplace
- On-Demand Services
- Consumer
- Mobile App
- Pet Sitting
---
