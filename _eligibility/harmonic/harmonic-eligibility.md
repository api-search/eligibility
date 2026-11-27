---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: This is a binding agreement (" Agreement ") between (i) you and the entity you represent
    type: business
  - text: If Customer is a state agency, state instrumentality, or public university, then solely to the extent, and only to the minimum extent, required by applicable Law
    type: government
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: High-Risk Applications
    text: You shall not use the Services, or deploy AI Customer Output, to make or to automate decisions in a High-Risk Application without sufficient human review
  - summary: No Personal Information submission
    text: You shall not submit Personal Information to the Services.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Harmonic may establish a trusted user program under which certain features of the Services are made available only to customers approved by Harmonic for that program
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Harmonic
provenance_date: '2026-11-09'
provider_name: Harmonic
provider_slug: harmonic
slug: harmonic-eligibility
source_date: '2026-11-09'
source_filename: harmonic-eligibility.yml
source_heading: Eligibility
source_page: https://www.harmonic.fun/legal/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Harmonic\naid: harmonic\nurl: https://www.harmonic.fun/legal/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: This is a binding agreement (\" Agreement \") between (i) you and the entity you represent\n- type: government\n  text: If Customer is a state agency, state instrumentality, or public university, then solely to the extent, and\n    only to the minimum extent, required by applicable Law\nrestricted_uses:\n- summary: High-Risk Applications\n  text: You shall not use the Services, or deploy AI Customer Output, to make or to\
  \ automate decisions in a High-Risk\n    Application without sufficient human review\n- summary: No Personal Information submission\n  text: You shall not submit Personal Information to the Services.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Harmonic may establish a trusted user program under which certain features of the Services are made available\n    only to customers approved by Harmonic for that program\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/harmonic/eligibility/harmonic-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 5 quoted statements, read from Harmonic's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Mathematics
- Formal Verification
- Theorem Proving
- Lean
- Machine Reasoning
- Developer Tools
---
