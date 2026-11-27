---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 (or the age of digital consent in your country, if higher)
    type: individual
  - text: if acting for an organisation, authorised to bind it
    type: business
  minimum_age:
    text: You must be at least 18 (or the age of digital consent in your country, if higher)
    value: '18'
  restricted_uses:
  - summary: Unlawful purposes
    text: use the Service for unlawful purposes
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
name: Structura
provenance_date: '2026-11-10'
provider_name: Structura
provider_slug: structura-tools
slug: structura-tools-eligibility
source_date: '2026-11-10'
source_filename: structura-tools-eligibility.yml
source_heading: Eligibility
source_page: https://structura.tools/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Structura\naid: structura-tools\nurl: https://structura.tools/legal/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 (or the age of digital consent in your country, if higher)\n- type: business\n  text: if acting for an organisation, authorised to bind it\nrestricted_uses:\n- summary: Unlawful purposes\n  text: use the Service for unlawful purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 (or the age of\
  \ digital consent in your country, if higher)\n"
source_yaml_url: https://artifacts.apis.io/structura-tools/eligibility/structura-tools-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Structura's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Code Generation
- Domain Modeling
- UML
- Software Architecture
- Low-Code
- Compliance
- MCP
---
