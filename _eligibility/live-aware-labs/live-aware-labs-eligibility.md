---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Services can be accessed from countries around the world and may contain references to features and services that are not available in Customer's country.
  entity_types:
  - text: such individual is over the age of 18 and is competent to enter binding agreements and contracts in such individual's jurisdiction of residence
    type: individual
  - text: such individual is authorized to contract on behalf of Customer and legally bind Customer
    type: business
  minimum_age:
    text: such individual is over the age of 18
    value: '18'
  restricted_uses:
  - summary: No financial or medical data
    text: Customer and its Authorized Users and Playtesters shall not transmit or provide to Live Aware Labs any financial or medical information of any nature
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
name: Live Aware Labs
provenance_date: '2026-11-09'
provider_name: Live Aware Labs
provider_slug: live-aware-labs
slug: live-aware-labs-eligibility
source_date: '2026-11-09'
source_filename: live-aware-labs-eligibility.yml
source_heading: Eligibility
source_page: https://www.liveaware.io/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Live Aware Labs\naid: live-aware-labs\nurl: https://www.liveaware.io/legal/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Services can be accessed from countries around the world and may contain references to features and\n    services that are not available in Customer's country.\nentity_types:\n- type: individual\n  text: such individual is over the age of 18 and is competent to enter binding agreements and contracts in such\n    individual's jurisdiction of residence\n- type: business\n  text: such individual is authorized to contract on behalf of Customer\
  \ and legally bind Customer\nrestricted_uses:\n- summary: No financial or medical data\n  text: Customer and its Authorized Users and Playtesters shall not transmit or provide to Live Aware Labs any financial\n    or medical information of any nature\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: such individual is over the age of 18\n"
source_yaml_url: https://artifacts.apis.io/live-aware-labs/eligibility/live-aware-labs-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Live Aware Labs's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Game Development
- Playtesting
- Player Analytics
- Game Analytics
- Video Telemetry
- Developer Tools
- Artificial Intelligence
---
