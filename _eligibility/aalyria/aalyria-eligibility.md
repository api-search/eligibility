---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old to use the Site or the Services.
    type: individual
  minimum_age:
    text: You must be at least 18 years old to use the Site or the Services.
    value: '18'
  restricted_uses:
  - summary: Illegal, harassing or infringing use
    text: violate any law or regulation; violate or infringe other people's intellectual property, privacy, publicity, or other legal rights
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
name: Aalyria
provenance_date: '2026-11-09'
provider_name: Aalyria
provider_slug: aalyria
slug: aalyria-eligibility
source_date: '2026-11-09'
source_filename: aalyria-eligibility.yml
source_heading: Eligibility
source_page: https://www.aalyria.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Aalyria\naid: aalyria\nurl: https://www.aalyria.com/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old to use the Site or the Services.\nrestricted_uses:\n- summary: Illegal, harassing or infringing use\n  text: violate any law or regulation; violate or infringe other people's intellectual property, privacy, publicity,\n    or other legal rights\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least\
  \ 18 years old to use the Site or the Services.\n"
source_yaml_url: https://artifacts.apis.io/aalyria/eligibility/aalyria-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Aalyria's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Networking
- Satellite
- Space
- Telecommunications
- Software Defined Networking
- Orchestration
- Aerospace
- Defense
- Connectivity
- gRPC
- Protocol Buffers
- Telemetry
- Optical Communications
---
