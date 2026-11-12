---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Each person or organisation should have one free account.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful or infringing content
    text: You must not use the service for unlawful purposes, in particular to convert or distribute content that is illegal or infringes the rights of others
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You create an account with your email address (confirmed with a one-time code) or by our invitation.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: conved.com
provenance_date: '2026-11-09'
provider_name: conved.com
provider_slug: conved-com
slug: conved-com-eligibility
source_date: '2026-11-09'
source_filename: conved-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.conved.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: conved.com\naid: conved-com\nurl: https://www.conved.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Each person or organisation should have one free account.\nrestricted_uses:\n- summary: Unlawful or infringing content\n  text: You must not use the service for unlawful purposes, in particular to convert or distribute content that\n    is illegal or infringes the rights of others\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You create an account with your email address (confirmed with a one-time\
  \ code) or by our invitation.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/conved-com/eligibility/conved-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from conved.com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- File Conversion
- Documents
- Images
- Media
- MCP
- CLI
- Developer Tools
---
