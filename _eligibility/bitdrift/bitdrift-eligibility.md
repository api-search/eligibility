---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Customer may not use the Services if located in, under the control of, or a national or resident of an Embargoed Country or Designated National.
  entity_types:
  - text: IF YOU ARE AN INDIVIDUAL AGREEING TO THESE TERMS ON BEHALF OF AN ENTITY, SUCH AS YOUR EMPLOYER, YOU REPRESENT THAT YOU HAVE THE LEGAL AUTHORITY TO BIND THAT ENTITY.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No unlawful or out-of-scope use
    text: (g) use the Services other than as described in this Agreement or the applicable Documentation, or for any unlawful purpose.
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
name: bitdrift
provenance_date: '2026-11-09'
provider_name: bitdrift
provider_slug: bitdrift
slug: bitdrift-eligibility
source_date: '2026-11-09'
source_filename: bitdrift-eligibility.yml
source_heading: Eligibility
source_page: https://docs.bitdrift.io/support/tos-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: bitdrift\naid: bitdrift\nurl: https://docs.bitdrift.io/support/tos-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Customer may not use the Services if located in, under the control of, or a national or resident of an Embargoed\n    Country or Designated National.\nentity_types:\n- type: business\n  text: IF YOU ARE AN INDIVIDUAL AGREEING TO THESE TERMS ON BEHALF OF AN ENTITY, SUCH AS YOUR EMPLOYER, YOU REPRESENT\n    THAT YOU HAVE THE LEGAL AUTHORITY TO BIND THAT ENTITY.\nrestricted_uses:\n- summary: No unlawful or out-of-scope use\n  text: (g) use the Services other than\
  \ as described in this Agreement or the applicable Documentation, or for any\n    unlawful purpose.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/bitdrift/eligibility/bitdrift-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from bitdrift's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Developer Tools
- Observability
- Mobile
- Monitoring
- Logging
- Crash Reporting
- Session Replay
- SDK
- gRPC
- Telemetry
---
