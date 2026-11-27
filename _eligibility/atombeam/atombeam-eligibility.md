---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 13 years old to use this Website. However, children of all ages may use the Website if enabled by a parent or legal guardian.
    type: individual
  minimum_age:
    text: You must be at least 13 years old to use this Website.
    value: '13'
  restricted_uses:
  - summary: Unlawful or harmful use
    text: 'You agree not to use the Website: In any way that violates any applicable federal, state, local or international law or regulation'
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
name: AtomBeam
provenance_date: '2026-11-09'
provider_name: AtomBeam
provider_slug: atombeam
slug: atombeam-eligibility
source_date: '2026-11-09'
source_filename: atombeam-eligibility.yml
source_heading: Eligibility
source_page: https://www.atombeamtech.com/utility/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AtomBeam\naid: atombeam\nurl: https://www.atombeamtech.com/utility/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 13 years old to use this Website. However, children of all ages may use the Website\n    if enabled by a parent or legal guardian.\nrestricted_uses:\n- summary: Unlawful or harmful use\n  text: 'You agree not to use the Website: In any way that violates any applicable federal, state, local or international\n    law or regulation'\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: '13'\n  text: You must be at least 13 years old to use this Website.\n"
source_yaml_url: https://artifacts.apis.io/atombeam/eligibility/atombeam-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from AtomBeam's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Data Compression
- IoT
- Edge Computing
- Satellite Communications
- Machine Learning
- Data Management
- Defense
- Telemetry
---
