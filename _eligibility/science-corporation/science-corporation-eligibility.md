---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Services are intended for use by residents of the United States. We do not intentionally provide access to the Services to individuals located elsewhere.
  entity_types:
  - text: you affirm that you (i) are have reached the age of majority in your jurisdiction of residence
    type: individual
  - text: If you are using the Services on behalf of a company, organization, or other entity, you further affirm that you have authority to bind that organization to these Terms
    type: business
  minimum_age:
    text: you affirm that you (i) are have reached the age of majority in your jurisdiction of residence
    value: age of majority
  restricted_uses:
  - summary: No harm to minors
    text: use the Services for the purpose of exploiting, harming, or attempting to exploit or harm minors in any way
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
name: Science Corporation
provenance_date: '2026-11-10'
provider_name: Science Corporation
provider_slug: science-corporation
slug: science-corporation-eligibility
source_date: '2026-11-10'
source_filename: science-corporation-eligibility.yml
source_heading: Eligibility
source_page: https://science.xyz/legal/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Science Corporation\naid: science-corporation\nurl: https://science.xyz/legal/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Services are intended for use by residents of the United States. We do not intentionally provide access\n    to the Services to individuals located elsewhere.\nentity_types:\n- type: individual\n  text: you affirm that you (i) are have reached the age of majority in your jurisdiction of residence\n- type: business\n  text: If you are using the Services on behalf of a company, organization, or other entity, you further affirm\n    that you have\
  \ authority to bind that organization to these Terms\nrestricted_uses:\n- summary: No harm to minors\n  text: use the Services for the purpose of exploiting, harming, or attempting to exploit or harm minors in any\n    way\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: age of majority\n  text: you affirm that you (i) are have reached the age of majority in your jurisdiction of residence\n"
source_yaml_url: https://artifacts.apis.io/science-corporation/eligibility/science-corporation-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Science Corporation's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Neurotechnology
- Brain-Computer Interface
- Neural Interface
- Medical Devices
- gRPC
- Protocol Buffers
- Streaming
- Neuroscience
- Bioelectronics
---
