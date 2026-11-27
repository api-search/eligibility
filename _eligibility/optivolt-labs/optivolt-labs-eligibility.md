---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you accept on behalf of an entity, you have the authority to bind that entity.
    type: business
  minimum_age:
    text: You must be 18+.
    value: '18'
  restricted_uses:
  - summary: High-risk activities
    text: The Service is not designed for use where failure could lead to death, personal injury, or environmental damage ("High-Risk Activities"). Do not use the Service for High-Risk Activities.
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
name: Optivolt Labs
provenance_date: '2026-11-10'
provider_name: Optivolt Labs
provider_slug: optivolt-labs
slug: optivolt-labs-eligibility
source_date: '2026-11-10'
source_filename: optivolt-labs-eligibility.yml
source_heading: Eligibility
source_page: https://optivolt.com/legal/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Optivolt Labs\naid: optivolt-labs\nurl: https://optivolt.com/legal/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you accept on behalf of an entity, you have the authority to bind that entity.\nrestricted_uses:\n- summary: High-risk activities\n  text: The Service is not designed for use where failure could lead to death, personal injury, or environmental\n    damage (\"High-Risk Activities\"). Do not use the Service for High-Risk Activities.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n\
  \  text: null\nminimum_age:\n  value: '18'\n  text: You must be 18+.\n"
source_yaml_url: https://artifacts.apis.io/optivolt-labs/eligibility/optivolt-labs-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Optivolt Labs's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Solar
- Energy
- Clean Energy
- Hardware
- Power Electronics
- Solar Monitoring
- IoT
- Battery Management
- Renewable Energy
- Software-as-a-Service
---
