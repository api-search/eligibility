---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Service is controlled and operated from facilities in the People’s Republic of China (PRC) and the United States (US). DJI makes no representations that the Service is appropriate or available for use in other locations.
  entity_types:
  - text: If you create an account on behalf of a company, organization, or other entity, then (i) “you” includes you and that entity
    type: business
  minimum_age:
    text: Any use or access to the Service by anyone under thirteen is strictly prohibited and in violation of this TOU.
    value: '13'
  restricted_uses:
  - summary: Users previously removed
    text: The Service is not available to any Users previously removed from the Service by DJI.
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
name: DJI
provenance_date: '2026-11-09'
provider_name: DJI
provider_slug: dji
slug: dji-eligibility
source_date: '2026-11-09'
source_filename: dji-eligibility.yml
source_heading: Eligibility
source_page: https://developer.dji.com/policies/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: DJI\naid: dji\nurl: https://developer.dji.com/policies/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Service is controlled and operated from facilities in the People’s Republic of China (PRC) and the United\n    States (US). DJI makes no representations that the Service is appropriate or available for use in other locations.\nentity_types:\n- type: business\n  text: If you create an account on behalf of a company, organization, or other entity, then (i) “you” includes\n    you and that entity\nrestricted_uses:\n- summary: Users previously removed\n  text: The Service\
  \ is not available to any Users previously removed from the Service by DJI.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: Any use or access to the Service by anyone under thirteen is strictly prohibited and in violation of this\n    TOU.\n"
source_yaml_url: https://artifacts.apis.io/dji/eligibility/dji-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from DJI's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Drones
- UAV
- Aerial Imaging
- Robotics
- SDK
- Geospatial
- Hardware
- Enterprise
- Developer Platform
---
