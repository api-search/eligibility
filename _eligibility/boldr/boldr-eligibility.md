---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: BOLDR makes no representations that BOLDR are appropriate or available for use in other locations.
  entity_types:
  - text: (3) YOU HAVE THE AUTHORITY TO ENTER INTO THE TERMS ON BEHALF OF YOURSELF OR THE COMPANY YOU WORK FOR, AND TO BIND THAT COMPANY TO THESE TERMS.
    type: business
  minimum_age:
    text: YOU ARE OF LEGAL AGE TO FORM A BINDING CONTRACT WITH BOLDR
    value: null
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
name: Boldr
provenance_date: '2026-11-09'
provider_name: Boldr
provider_slug: boldr
slug: boldr-eligibility
source_date: '2026-11-09'
source_filename: boldr-eligibility.yml
source_heading: Eligibility
source_page: https://shopboldr.com/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Boldr\naid: boldr\nurl: https://shopboldr.com/policies/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: BOLDR makes no representations that BOLDR are appropriate or available for use in other locations.\nentity_types:\n- type: business\n  text: (3) YOU HAVE THE AUTHORITY TO ENTER INTO THE TERMS ON BEHALF OF YOURSELF OR THE COMPANY YOU WORK FOR, AND\n    TO BIND THAT COMPANY TO THESE TERMS.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: YOU ARE OF LEGAL AGE TO FORM A BINDING\
  \ CONTRACT WITH BOLDR\n"
source_yaml_url: https://artifacts.apis.io/boldr/eligibility/boldr-eligibility.yml
stated_fields:
- countries
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from Boldr's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Smart Home
- Energy
- Climate Control
- IoT
- Consumer Hardware
- Thermostat
- HVAC
- E-Commerce
---
