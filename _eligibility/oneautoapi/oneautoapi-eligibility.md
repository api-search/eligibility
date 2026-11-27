---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Customer wishes to use One Auto API's services in its business operations.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No PPI or payday loan marketing
    text: for the marketing or promotion of any services in connection with payday loans or the reclaim of Payment Protection Insurance ('PPI')
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
name: One Auto API
provenance_date: '2026-11-10'
provider_name: One Auto API
provider_slug: oneautoapi
slug: oneautoapi-eligibility
source_date: '2026-11-10'
source_filename: oneautoapi-eligibility.yml
source_heading: Eligibility
source_page: https://www.oneautoapi.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: One Auto API\naid: oneautoapi\nurl: https://www.oneautoapi.com/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The Customer wishes to use One Auto API's services in its business operations.\nrestricted_uses:\n- summary: No PPI or payday loan marketing\n  text: for the marketing or promotion of any services in connection with payday loans or the reclaim of Payment\n    Protection Insurance ('PPI')\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n\
  \  text: null\n"
source_yaml_url: https://artifacts.apis.io/oneautoapi/eligibility/oneautoapi-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from One Auto API's own page on 2026-11-10.
synthetic: false
tags:
- Automotive
- Data
- Vehicles
- United Kingdom
---
