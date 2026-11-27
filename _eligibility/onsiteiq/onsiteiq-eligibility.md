---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: OnsiteIQ makes no representations that the Services are appropriate or available for use in other locations.
  entity_types:
  - text: represent you are of legal age in your jurisdiction of residence to form a binding contract with OnsiteIQ
    type: individual
  minimum_age:
    text: represent you are of legal age in your jurisdiction of residence to form a binding contract with OnsiteIQ
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
name: OnsiteIQ
provenance_date: '2026-11-10'
provider_name: OnsiteIQ
provider_slug: onsiteiq
slug: onsiteiq-eligibility
source_date: '2026-11-10'
source_filename: onsiteiq-eligibility.yml
source_heading: Eligibility
source_page: https://onsiteiq.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: OnsiteIQ\naid: onsiteiq\nurl: https://onsiteiq.com/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: OnsiteIQ makes no representations that the Services are appropriate or available for use in other locations.\nentity_types:\n- type: individual\n  text: represent you are of legal age in your jurisdiction of residence to form a binding contract with OnsiteIQ\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: represent you are of legal age in your jurisdiction of residence to form\
  \ a binding contract with OnsiteIQ\n"
source_yaml_url: https://artifacts.apis.io/onsiteiq/eligibility/onsiteiq-eligibility.yml
stated_fields:
- countries
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from OnsiteIQ's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Construction
- Construction Technology
- Reality Capture
- 360 Imaging
- Computer Vision
- Artificial Intelligence
- Real Estate
- Project Management
- Construction Monitoring
---
