---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: IF YOU ARE ENTERING INTO THESE TERMS OF SERVICE ON BEHALF OF A COMPANY OR OTHER LEGAL ENTITY, YOU REPRESENT THAT YOU HAVE THE AUTHORITY TO BIND SUCH ENTITY
    type: business
  - text: IF YOU ARE ENTERING INTO THESE TERMS OF SERVICE AS AN INDIVIDUAL, THE TERM “CUSTOMER” REFERS TO YOU.
    type: individual
  minimum_age:
    text: THE SITE AND THE PRODUCTS ARE NOT AVAILABLE TO INDIVIDUALS UNDER THE AGE OF 18.
    value: '18'
  restricted_uses:
  - summary: Services not for service bureau use
    text: Customer shall use the Services and Software only for its own internal business operations, and not for the operation of a service bureau or timesharing service.
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
name: BevSpot
provenance_date: '2026-11-09'
provider_name: BevSpot
provider_slug: bevspot
slug: bevspot-eligibility
source_date: '2026-11-09'
source_filename: bevspot-eligibility.yml
source_heading: Eligibility
source_page: https://bevspot.com/terms-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BevSpot\naid: bevspot\nurl: https://bevspot.com/terms-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: IF YOU ARE ENTERING INTO THESE TERMS OF SERVICE ON BEHALF OF A COMPANY OR OTHER LEGAL ENTITY, YOU REPRESENT\n    THAT YOU HAVE THE AUTHORITY TO BIND SUCH ENTITY\n- type: individual\n  text: IF YOU ARE ENTERING INTO THESE TERMS OF SERVICE AS AN INDIVIDUAL, THE TERM “CUSTOMER” REFERS TO YOU.\nrestricted_uses:\n- summary: Services not for service bureau use\n  text: Customer shall use the Services and Software only for its own\
  \ internal business operations, and not for\n    the operation of a service bureau or timesharing service.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: THE SITE AND THE PRODUCTS ARE NOT AVAILABLE TO INDIVIDUALS UNDER THE AGE OF 18.\n"
source_yaml_url: https://artifacts.apis.io/bevspot/eligibility/bevspot-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from BevSpot's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Ai Apps
- Restaurant
- Hospitality
- Inventory
- Food and Beverage
- Point-of-Sale
- Analytics
- Software-as-a-Service
---
