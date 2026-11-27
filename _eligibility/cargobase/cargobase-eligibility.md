---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Platform is offered for business purposes only and cannot be used for personal, household, or consumer purposes.
    type: business
  - text: You are a human individual or an individual acting on behalf of a business entity, and not a machine
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No personal or consumer use
    text: The Platform is offered for business purposes only and cannot be used for personal, household, or consumer purposes.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Cargobase reserves the right to limit or refuse the registration of the Account for any reason whatsoever.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Cargobase
provenance_date: '2026-11-09'
provider_name: Cargobase
provider_slug: cargobase
slug: cargobase-eligibility
source_date: '2026-11-09'
source_filename: cargobase-eligibility.yml
source_heading: Eligibility
source_page: https://www.cargobase.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cargobase\naid: cargobase\nurl: https://www.cargobase.com/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The Platform is offered for business purposes only and cannot be used for personal, household, or consumer\n    purposes.\n- type: individual\n  text: You are a human individual or an individual acting on behalf of a business entity, and not a machine\nrestricted_uses:\n- summary: No personal or consumer use\n  text: The Platform is offered for business purposes only and cannot be used for personal, household,\
  \ or consumer\n    purposes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Cargobase reserves the right to limit or refuse the registration of the Account for any reason whatsoever.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/cargobase/eligibility/cargobase-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from Cargobase's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Logistics
- Transportation Management System
- Freight
- Supply Chain
- Spot Freight
- Freight Procurement
- Shipping
---
