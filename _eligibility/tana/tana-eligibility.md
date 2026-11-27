---
api_specs:
- filename: tana-addtonodev2-api-openapi.yml
  format: yaml
  label: Tana AddToNodeV2 API
  slug: tana-addtonodev2-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tana/openapi/tana-addtonodev2-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You represent and warrant that (i) you are not located in a country that is subject to a U.S. Government embargo, or that has been designated by the U.S. Government as a “terrorist supporting” country
  entity_types:
  - text: If you are accessing or using the Service on behalf of a business or entity, then your business or entity is legally and financially responsible for your access to and use of the Service
    type: business
  - text: 'Individual consumers, please note: section 20.2.1 (arbitration agreement) contains provisions that govern how to resolve disputes between you and Tana.'
    type: individual
  minimum_age:
    text: To register an account and access the Service, you must be at least thirteen years old or older.
    value: '13'
  restricted_uses:
  - summary: Prohibited conduct
    text: Use the Service for illegal, harassing, unethical, or disruptive purposes
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
name: Tana
provenance_date: '2026-11-10'
provider_name: Tana
provider_slug: tana
slug: tana-eligibility
source_date: '2026-11-10'
source_filename: tana-eligibility.yml
source_heading: Eligibility
source_page: https://tana.inc/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Tana\naid: tana\nurl: https://tana.inc/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You represent and warrant that (i) you are not located in a country that is subject to a U.S. Government\n    embargo, or that has been designated by the U.S. Government as a “terrorist supporting” country\nentity_types:\n- type: business\n  text: If you are accessing or using the Service on behalf of a business or entity, then your business or entity\n    is legally and financially responsible for your access to and use of the Service\n- type: individual\n  text: 'Individual consumers, please\
  \ note: section 20.2.1 (arbitration agreement) contains provisions that govern\n    how to resolve disputes between you and Tana.'\nrestricted_uses:\n- summary: Prohibited conduct\n  text: Use the Service for illegal, harassing, unethical, or disruptive purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: To register an account and access the Service, you must be at least thirteen years old or older.\n"
source_yaml_url: https://artifacts.apis.io/tana/eligibility/tana-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Tana's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Note Taking
- Knowledge Management
- Productivity
- Artificial Intelligence
- Meetings
- Agents
- Collaboration
- Outliner
---
