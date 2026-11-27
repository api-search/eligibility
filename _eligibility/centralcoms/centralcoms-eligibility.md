---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Service is for business use.
    type: business
  minimum_age:
    text: You must be at least 18 years old and able to form a binding contract to use it.
    value: '18'
  restricted_uses:
  - summary: Children's data and high-risk activities
    text: Process data of children knowingly, or use the Service for high-risk activities where failure could cause serious harm
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
name: CentralComs
provenance_date: '2026-11-09'
provider_name: CentralComs
provider_slug: centralcoms
slug: centralcoms-eligibility
source_date: '2026-11-09'
source_filename: centralcoms-eligibility.yml
source_heading: Eligibility
source_page: https://www.centralcoms.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CentralComs\naid: centralcoms\nurl: https://www.centralcoms.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The Service is for business use.\nrestricted_uses:\n- summary: Children's data and high-risk activities\n  text: Process data of children knowingly, or use the Service for high-risk activities where failure could cause\n    serious harm\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and able to form a binding contract\
  \ to use it.\n"
source_yaml_url: https://artifacts.apis.io/centralcoms/eligibility/centralcoms-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from CentralComs's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Property Management
- Real Estate Technology
- PropTech
- AI Agents
- Maintenance Coordination
- Leasing
- Vendor Coordination
- Y Combinator
---
