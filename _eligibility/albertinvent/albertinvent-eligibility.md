---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You may use the Services only if you are 16 years or older and capable of forming a binding contract with Albert or a partner of Albert
    type: individual
  - text: Albert Software Subscription Agreement executed by your organization
    type: business
  minimum_age:
    text: You may use the Services only if you are 16 years or older
    value: '16'
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
name: Albertinvent
provenance_date: '2026-11-09'
provider_name: Albertinvent
provider_slug: albertinvent
slug: albertinvent-eligibility
source_date: '2026-11-09'
source_filename: albertinvent-eligibility.yml
source_heading: Eligibility
source_page: https://www.albertinvent.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Albertinvent\naid: albertinvent\nurl: https://www.albertinvent.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You may use the Services only if you are 16 years or older and capable of forming a binding contract with\n    Albert or a partner of Albert\n- type: business\n  text: Albert Software Subscription Agreement executed by your organization\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: You may use the Services only\
  \ if you are 16 years or older\n"
source_yaml_url: https://artifacts.apis.io/albertinvent/eligibility/albertinvent-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from Albertinvent's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Developer Tools
- Chemistry
- Materials Science
- Research and Development
- Artificial Intelligence
- Laboratory Informatics
- Data Management
- Software-as-a-Service
---
