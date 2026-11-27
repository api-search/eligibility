---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: IF YOU ARE ENTERING INTO THESE TERMS OF SERVICE AS AN INDIVIDUAL
    type: individual
  - text: If you are entering into this Terms of Service on behalf of a company, business or other legal entity, you represent that you have the authority to bind such entity and its affiliates to this Terms of Service
    type: business
  minimum_age:
    text: If you are under 13 years of age, you are not authorized to use the Service, with or without registering. In addition, if you are under 18 years old, you may use the Service, with or without registering, only with the express consent of your parent or guardian
    value: '13'
  restricted_uses:
  - summary: Competitors barred from access
    text: No employee, independent contractor, agent, or affiliate of any competing delivery service-related company is permitted to view, access, or use any portion of the Service without express written permission from Delivery Collective.
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
name: Delivery Collective
provenance_date: '2026-11-09'
provider_name: Delivery Collective
provider_slug: delivery-collective
slug: delivery-collective-eligibility
source_date: '2026-11-09'
source_filename: delivery-collective-eligibility.yml
source_heading: Eligibility
source_page: https://withbites.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Delivery Collective\naid: delivery-collective\nurl: https://withbites.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: IF YOU ARE ENTERING INTO THESE TERMS OF SERVICE AS AN INDIVIDUAL\n- type: business\n  text: If you are entering into this Terms of Service on behalf of a company, business or other legal entity, you\n    represent that you have the authority to bind such entity and its affiliates to this Terms of Service\nrestricted_uses:\n- summary: Competitors barred from access\n  text: No employee, independent\
  \ contractor, agent, or affiliate of any competing delivery service-related company\n    is permitted to view, access, or use any portion of the Service without express written permission from Delivery\n    Collective.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: If you are under 13 years of age, you are not authorized to use the Service, with or without registering.\n    In addition, if you are under 18 years old, you may use the Service, with or without registering, only with\n    the express consent of your parent or guardian\n"
source_yaml_url: https://artifacts.apis.io/delivery-collective/eligibility/delivery-collective-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Delivery Collective's own page on 2026-11-09.
synthetic: false
tags:
- Food Delivery
- Artificial Intelligence
- Marketplace
- Fair Pricing
- Restaurant
---
