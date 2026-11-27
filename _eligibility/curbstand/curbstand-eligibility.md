---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: the individual or entity enrolling in Curbstand’s Monthly Parking Service
    type: individual
  - text: If you are signing up for monthly parking on behalf of a business or other entity, you represent that you have the legal authority to bind that entity to these terms
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Vehicle storage and misuse
    text: Parking of vehicles for the purpose of storage (long-term holding without regular use) is not permitted without prior written agreement.
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
name: CurbStand
provenance_date: '2026-11-09'
provider_name: CurbStand
provider_slug: curbstand
slug: curbstand-eligibility
source_date: '2026-11-09'
source_filename: curbstand-eligibility.yml
source_heading: Eligibility
source_page: https://curbstand.com/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CurbStand\naid: curbstand\nurl: https://curbstand.com/terms-and-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: the individual or entity enrolling in Curbstand’s Monthly Parking Service\n- type: business\n  text: If you are signing up for monthly parking on behalf of a business or other entity, you represent that you\n    have the legal authority to bind that entity to these terms\nrestricted_uses:\n- summary: Vehicle storage and misuse\n  text: Parking of vehicles for the purpose of storage (long-term holding without regular\
  \ use) is not permitted\n    without prior written agreement.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/curbstand/eligibility/curbstand-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from CurbStand's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Valet
- Parking
- Car Wash
- Los Angeles
---
