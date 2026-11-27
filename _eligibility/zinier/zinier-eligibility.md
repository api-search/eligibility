---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: by Zinier Inc., a company organized under the laws of Delaware, or if your domicile is registered within Europe or the United Kingdom, by Zinier UK Limited
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Time-critical or mission-critical functions
    text: will not be used, and are not licensed for use, in connection with any of Customer’s time-critical or mission-critical functions
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
name: Zinier
provenance_date: '2026-11-10'
provider_name: Zinier
provider_slug: zinier
slug: zinier-eligibility
source_date: '2026-11-10'
source_filename: zinier-eligibility.yml
source_heading: Eligibility
source_page: https://www.zinier.com/legal/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Zinier\naid: zinier\nurl: https://www.zinier.com/legal/terms-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: by Zinier Inc., a company organized under the laws of Delaware, or if your domicile is registered within\n    Europe or the United Kingdom, by Zinier UK Limited\nrestricted_uses:\n- summary: Time-critical or mission-critical functions\n  text: will not be used, and are not licensed for use, in connection with any of Customer’s time-critical or mission-critical\n    functions\nverification:\n  kyc: null\n  kyb: null\n\
  \  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/zinier/eligibility/zinier-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Zinier's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Field Service Management
- No-Code
- Workflow Automation
- Enterprise Software
---
