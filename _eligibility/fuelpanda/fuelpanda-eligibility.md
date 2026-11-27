---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Customer represents and warrants to FleetPanda that Customer is acquiring the right to access and use the Software, and agreeing to these terms, for the purposes of a business
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Usage limits on users
    text: the User identification cannot be shared with any other person.
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
name: FleetPanda
provenance_date: '2026-11-09'
provider_name: FleetPanda
provider_slug: fuelpanda
slug: fuelpanda-eligibility
source_date: '2026-11-09'
source_filename: fuelpanda-eligibility.yml
source_heading: Eligibility
source_page: https://www.fleetpanda.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: FleetPanda\naid: fuelpanda\nurl: https://www.fleetpanda.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Customer represents and warrants to FleetPanda that Customer is acquiring the right to access and use the\n    Software, and agreeing to these terms, for the purposes of a business\nrestricted_uses:\n- summary: Usage limits on users\n  text: the User identification cannot be shared with any other person.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n\
  \  text: null\n"
source_yaml_url: https://artifacts.apis.io/fuelpanda/eligibility/fuelpanda-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from FleetPanda's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fuel Distribution
- Fleet Management
- Dispatch
- Delivery Logistics
- Energy
- Transportation
- Software-as-a-Service
---
