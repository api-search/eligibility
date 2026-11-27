---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Cannon VoIP serves customers primarily in the United States and may also serve international customers.
  entity_types:
  - text: Serving businesses nationwide
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export and sanctions restrictions
    text: Customer agrees that it will not divert, use, export, or re-export any Products or Services contrary to United States export control or sanctions laws.
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
name: Cannon VoIP
provenance_date: '2026-11-09'
provider_name: Cannon VoIP
provider_slug: cannonvoip-com
slug: cannonvoip-com-eligibility
source_date: '2026-11-09'
source_filename: cannonvoip-com-eligibility.yml
source_heading: Eligibility
source_page: https://cannonvoip.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cannon VoIP\naid: cannonvoip-com\nurl: https://cannonvoip.com/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: Cannon VoIP serves customers primarily in the United States and may also serve international customers.\nentity_types:\n- type: business\n  text: Serving businesses nationwide\nrestricted_uses:\n- summary: Export and sanctions restrictions\n  text: Customer agrees that it will not divert, use, export, or re-export any Products or Services contrary to\n    United States export control or sanctions laws.\nverification:\n  kyc: null\n\
  \  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/cannonvoip-com/eligibility/cannonvoip-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Cannon VoIP's own page on 2026-11-09.
synthetic: false
tags:
- VoIP
- Business Communications
- Cloud Phone System
- US
- Software-as-a-Service
---
