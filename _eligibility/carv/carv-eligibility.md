---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 'Client: the private person or legal entity who entered into an Agreement with Carv.com.'
    type: individual
  - text: 'Client: the private person or legal entity who entered into an Agreement with Carv.com.'
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Prohibited content and purposes
    text: 'It is not permitted to use the Service including Carv for a purpose listed below or make Content available:'
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
name: CARV
provenance_date: '2026-11-09'
provider_name: CARV
provider_slug: carv
slug: carv-eligibility
source_date: '2026-11-09'
source_filename: carv-eligibility.yml
source_heading: Eligibility
source_page: https://www.carv.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CARV\naid: carv\nurl: https://www.carv.com/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: 'Client: the private person or legal entity who entered into an Agreement with Carv.com.'\n- type: business\n  text: 'Client: the private person or legal entity who entered into an Agreement with Carv.com.'\nrestricted_uses:\n- summary: Prohibited content and purposes\n  text: 'It is not permitted to use the Service including Carv for a purpose listed below or make Content available:'\nverification:\n  kyc: null\n  kyb: null\n\
  \  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/carv/eligibility/carv-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from CARV's own page on 2026-11-09.
synthetic: false
tags:
- Hiring
- AI Recruiting
- Volume Hiring
- Staffing
- Automation
---
