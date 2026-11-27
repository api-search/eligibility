---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: whether you are acting in your individual capacity or on behalf of a company or other organization
    type: individual
  - text: or on behalf of a company or other organization
    type: business
  minimum_age:
    text: you are of legal age in the jurisdiction where you reside;
    value: legal age
  restricted_uses:
  - summary: Unlawful or unauthorized purpose
    text: Our Services must not be used for any unlawful or unauthorized purpose, and we expressly prohibit such use.
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
name: Motomarks
provenance_date: '2026-11-10'
provider_name: Motomarks
provider_slug: motomarks
slug: motomarks-eligibility
source_date: '2026-11-10'
source_filename: motomarks-eligibility.yml
source_heading: Eligibility
source_page: https://motomarks.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Motomarks\naid: motomarks\nurl: https://motomarks.io/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: whether you are acting in your individual capacity or on behalf of a company or other organization\n- type: business\n  text: or on behalf of a company or other organization\nrestricted_uses:\n- summary: Unlawful or unauthorized purpose\n  text: Our Services must not be used for any unlawful or unauthorized purpose, and we expressly prohibit such use.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text:\
  \ null\nminimum_age:\n  value: legal age\n  text: you are of legal age in the jurisdiction where you reside;\n"
source_yaml_url: https://artifacts.apis.io/motomarks/eligibility/motomarks-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Motomarks's own page on 2026-11-10.
synthetic: false
tags:
- Automotive
- Logo
- Image CDN
- Manufacturer
- Brand Assets
- Image
- CDN
- Developer Tools
- Agent-Native
- MCP
- Reference Data
---
