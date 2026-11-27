---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are entering into this Agreement on behalf of a company or other legal entity, you represent that you have the authority to bind such entity
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Lawful purposes only
    text: you may only use the Services for lawful purposes
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
name: Shiftsmart
provenance_date: '2026-11-10'
provider_name: Shiftsmart
provider_slug: shiftsmart
slug: shiftsmart-eligibility
source_date: '2026-11-10'
source_filename: shiftsmart-eligibility.yml
source_heading: Eligibility
source_page: https://shiftsmart.com/en-us/employer-terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Shiftsmart\naid: shiftsmart\nurl: https://shiftsmart.com/en-us/employer-terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are entering into this Agreement on behalf of a company or other legal entity, you represent that\n    you have the authority to bind such entity\nrestricted_uses:\n- summary: Lawful purposes only\n  text: you may only use the Services for lawful purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/shiftsmart/eligibility/shiftsmart-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Shiftsmart's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Workforce Management
- Staffing
- Scheduling
- Labor Marketplace
- Human Resources
- Gig Economy
- Workforce
- Payments
- Field Service Management
---
