---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: One person or entity may not maintain more than one free account.
    type: individual
  minimum_age:
    text: You must be at least 16 years old to use the Service.
    value: '16'
  restricted_uses:
  - summary: Unlawful use
    text: Violate any applicable laws or regulations.
  - summary: Unauthorized access
    text: Attempt to gain unauthorized access to other systems.
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
name: MCPForge
provenance_date: '2026-11-10'
provider_name: MCPForge
provider_slug: mcpforge
slug: mcpforge-eligibility
source_date: '2026-11-10'
source_filename: mcpforge-eligibility.yml
source_heading: Eligibility
source_page: https://mcpforge.tech/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: MCPForge\naid: mcpforge\nurl: https://mcpforge.tech/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: One person or entity may not maintain more than one free account.\nrestricted_uses:\n- summary: Unlawful use\n  text: Violate any applicable laws or regulations.\n- summary: Unauthorized access\n  text: Attempt to gain unauthorized access to other systems.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: You must be at least 16 years old to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/mcpforge/eligibility/mcpforge-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from MCPForge's own page on 2026-11-10.
synthetic: false
tags:
- Company
- MCP
- Verification
- Security
- Platform
---
