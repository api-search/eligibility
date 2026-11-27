---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If a User is an individual, a User may only use the Services if such User is at least eighteen (18) years of age.
    type: individual
  minimum_age:
    text: If a User is an individual, a User may only use the Services if such User is at least eighteen (18) years of age.
    value: '18'
  restricted_uses:
  - summary: Illegal conduct
    text: You shall not use the Services to engage in any illegal conduct;
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
name: NEXT Trucking
provenance_date: '2026-11-10'
provider_name: NEXT Trucking
provider_slug: next-trucking
slug: next-trucking-eligibility
source_date: '2026-11-10'
source_filename: next-trucking-eligibility.yml
source_heading: Eligibility
source_page: https://nexttrucking.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: NEXT Trucking\naid: next-trucking\nurl: https://nexttrucking.com/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: If a User is an individual, a User may only use the Services if such User is at least eighteen (18) years\n    of age.\nrestricted_uses:\n- summary: Illegal conduct\n  text: You shall not use the Services to engage in any illegal conduct;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: If a User is an individual, a User may only use\
  \ the Services if such User is at least eighteen (18) years\n    of age.\n"
source_yaml_url: https://artifacts.apis.io/next-trucking/eligibility/next-trucking-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from NEXT Trucking's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Logistics
- Freight
- Trucking
- Drayage
- Supply Chain
- Transportation
- Marketplace
- Transportation Management
- Shipping
---
