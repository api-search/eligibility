---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: No countries named as served. Export clause bars use by or transfers to embargoed countries and listed persons, without naming countries.
  entity_types:
  - text: IF YOU ARE AGREEING TO THESE TERMS AS AN INDIVIDUAL
    type: individual
  - text: IF YOU ARE AGREEING TO THESE TERMS AS A REPRESENTATIVE OF AN ENTITY, YOU REPRESENT THAT YOU HAVE THE AUTHORITY TO BIND THAT ENTITY
    type: business
  minimum_age:
    text: IF USER IS NOT AT LEAST 13 YEARS OLD, USER MAY NOT USE THE TRACEAIR PLATFORM.
    value: '13'
  restricted_uses:
  - summary: Export and embargo restrictions
    text: the Services shall not be used, and none of the underlying information, software, or technology may be transferred or otherwise exported or re-exported to countries as to which the United States maintains an embargo
  - summary: No illegal or inappropriate use
    text: not to use the TraceAir Platform for illegal, fraudulent, unethical or inappropriate purposes
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
name: TraceAir
provenance_date: '2026-11-10'
provider_name: TraceAir
provider_slug: traceair
slug: traceair-eligibility
source_date: '2026-11-10'
source_filename: traceair-eligibility.yml
source_heading: Eligibility
source_page: https://www.traceair.net/legal/eula
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: TraceAir\naid: traceair\nurl: https://www.traceair.net/legal/eula\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: No countries named as served. Export clause bars use by or transfers to embargoed countries and listed persons,\n    without naming countries.\nentity_types:\n- type: individual\n  text: IF YOU ARE AGREEING TO THESE TERMS AS AN INDIVIDUAL\n- type: business\n  text: IF YOU ARE AGREEING TO THESE TERMS AS A REPRESENTATIVE OF AN ENTITY, YOU REPRESENT THAT YOU HAVE THE AUTHORITY\n    TO BIND THAT ENTITY\nrestricted_uses:\n- summary: Export and embargo restrictions\n\
  \  text: the Services shall not be used, and none of the underlying information, software, or technology may be transferred\n    or otherwise exported or re-exported to countries as to which the United States maintains an embargo\n- summary: No illegal or inappropriate use\n  text: not to use the TraceAir Platform for illegal, fraudulent, unethical or inappropriate purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: IF USER IS NOT AT LEAST 13 YEARS OLD, USER MAY NOT USE THE TRACEAIR PLATFORM.\n"
source_yaml_url: https://artifacts.apis.io/traceair/eligibility/traceair-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from TraceAir's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Construction
- Site Intelligence
- Drones
- LiDAR
- Homebuilding
- Land Development
---
