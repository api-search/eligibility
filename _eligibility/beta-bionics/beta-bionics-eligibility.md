---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Company makes no representations that the Service is appropriate or available for use in other locations.
  entity_types:
  - text: IF YOU ARE ACCESSING OR USING THE SERVICE ON BEHALF OF AN ENTITY, ON BEHALF OF THE ENTITY IDENTIFIED IN THE ACCOUNT REGISTRATION PROCESS.
    type: business
  minimum_age:
    text: YOU ARE OF LEGAL AGE TO FORM A BINDING CONTRACT WITH COMPANY
    value: legal age
  restricted_uses:
  - summary: FDA approval compliance
    text: You further agree that your use of the Firmware and Application shall comply with any applicable U.S. Food and Drug Administration approvals, clearances, or authorizations for such products.
  - summary: Commercial activities and sales
    text: (C) involves commercial activities and/or sales, such as contests, sweepstakes, barter, advertising, or pyramid schemes without Company’s prior written consent.
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
name: Beta Bionics
provenance_date: '2026-11-09'
provider_name: Beta Bionics
provider_slug: beta-bionics
slug: beta-bionics-eligibility
source_date: '2026-11-09'
source_filename: beta-bionics-eligibility.yml
source_heading: Eligibility
source_page: https://www.betabionics.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Beta Bionics\naid: beta-bionics\nurl: https://www.betabionics.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: Company makes no representations that the Service is appropriate or available for use in other locations.\nentity_types:\n- type: business\n  text: IF YOU ARE ACCESSING OR USING THE SERVICE ON BEHALF OF AN ENTITY, ON BEHALF OF THE ENTITY IDENTIFIED IN\n    THE ACCOUNT REGISTRATION PROCESS.\nrestricted_uses:\n- summary: FDA approval compliance\n  text: You further agree that your use of the Firmware and Application shall comply with any applicable\
  \ U.S. Food\n    and Drug Administration approvals, clearances, or authorizations for such products.\n- summary: Commercial activities and sales\n  text: (C) involves commercial activities and/or sales, such as contests, sweepstakes, barter, advertising, or\n    pyramid schemes without Company’s prior written consent.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: legal age\n  text: YOU ARE OF LEGAL AGE TO FORM A BINDING CONTRACT WITH COMPANY\n"
source_yaml_url: https://artifacts.apis.io/beta-bionics/eligibility/beta-bionics-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Beta Bionics's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Health
- Healthcare
- Medical Devices
- Diabetes
- Automated Insulin Delivery
- Digital Health
- Remote Patient Monitoring
- HIPAA
- Connected Devices
---
