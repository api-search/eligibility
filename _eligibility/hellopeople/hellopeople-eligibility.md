---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served:
    - AU
    text: Jurisdiction Western Australia, Australia
  entity_types:
  - text: '"Client" and "you" refers to the person or entity engaging our services or accessing our website.'
    type: business
  minimum_age:
    text: null
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
name: HELLO PEOPLE
provenance_date: '2026-11-09'
provider_name: HELLO PEOPLE
provider_slug: hellopeople
slug: hellopeople-eligibility
source_date: '2026-11-09'
source_filename: hellopeople-eligibility.yml
source_heading: Eligibility
source_page: https://hellopeople.com.au/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: HELLO PEOPLE\naid: hellopeople\nurl: https://hellopeople.com.au/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - AU\n  excluded: []\n  text: Jurisdiction Western Australia, Australia\nentity_types:\n- type: business\n  text: '\"Client\" and \"you\" refers to the person or entity engaging our services or accessing our website.'\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/hellopeople/eligibility/hellopeople-eligibility.yml
stated_fields:
- countries
- entity_types
summary_line: 2 quoted statements, read from HELLO PEOPLE's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Integration
- Automation
- Software
---
