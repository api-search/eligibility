---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - FR
    - AD
    - BE
    - LU
    - MC
    - CH
    text: Andorre, Belgique, Guinée française, Luxembourg, Monaco, ou Suisse.
  entity_types:
  - text: Vous avez la qualité de professionnel
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Illegal or fraudulent activity
    text: exercer une activité illégale ou frauduleuse
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
name: Faks
provenance_date: '2026-11-09'
provider_name: Faks
provider_slug: faks
slug: faks-eligibility
source_date: '2026-11-09'
source_filename: faks-eligibility.yml
source_heading: Eligibility
source_page: https://www.faks.co/conditions-generales-de-services
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Faks\naid: faks\nurl: https://www.faks.co/conditions-generales-de-services\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - FR\n  - AD\n  - BE\n  - LU\n  - MC\n  - CH\n  excluded: []\n  text: Andorre, Belgique, Guinée française, Luxembourg, Monaco, ou Suisse.\nentity_types:\n- type: business\n  text: Vous avez la qualité de professionnel\nrestricted_uses:\n- summary: Illegal or fraudulent activity\n  text: exercer une activité illégale ou frauduleuse\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/faks/eligibility/faks-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Faks's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Pharmacy
- Healthcare
- Supplier Management
- Pharma
- Software-as-a-Service
- France
- Procurement
---
