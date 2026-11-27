---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Customer will not permit any Authorized User to access or use any Services in a U.S.-embargoed country or region or in violation of any U.S. export law or regulation.
  entity_types:
  - text: 'Customer shall not designate any person as an Authorized User unless such person is: (1) a natural person and (2) an employee of Customer.'
    type: business
  minimum_age:
    text: null
    value: null
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
name: Vendelux
provenance_date: '2026-11-10'
provider_name: Vendelux
provider_slug: vendelux
slug: vendelux-eligibility
source_date: '2026-11-10'
source_filename: vendelux-eligibility.yml
source_heading: Eligibility
source_page: https://vendelux.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Vendelux\naid: vendelux\nurl: https://vendelux.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Customer will not permit any Authorized User to access or use any Services in a U.S.-embargoed country or\n    region or in violation of any U.S. export law or regulation.\nentity_types:\n- type: business\n  text: 'Customer shall not designate any person as an Authorized User unless such person is: (1) a natural person\n    and (2) an employee of Customer.'\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value:\
  \ null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/vendelux/eligibility/vendelux-eligibility.yml
stated_fields:
- countries
- entity_types
summary_line: 2 quoted statements, read from Vendelux's own page on 2026-11-10.
synthetic: false
tags:
- Event Intelligence
- Event Marketing
- B2B Events
- Marketing Intelligence
- Sales Intelligence
- Event Data
- CRM Integration
- Demand Generation
- Field Marketing
- Conference Data
---
