---
api_specs:
- filename: usewire-io-openapi-generated.yml
  format: yaml
  label: usewire-io API
  slug: usewire-io-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/usewire-io/openapi/_ae-authored/usewire-io-openapi-generated.yml
claim_count: 7
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Wire uses globally distributed edge compute infrastructure, object storage, and serverless databases to deliver these services worldwide.
  entity_types:
  - text: You must be at least 13 years old to use Wire. If you are under 18, you must have permission from a parent or legal guardian.
    type: individual
  - text: You may create or join organizations.
    type: business
  minimum_age:
    text: You must be at least 13 years old to use Wire.
    value: '13'
  restricted_uses:
  - summary: Illegal content
    text: Store or process illegal content, including child exploitation material
  - summary: Cryptocurrency mining
    text: Use the Services for cryptocurrency mining
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: To use Wire, you must create an account.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: usewire-io
provenance_date: '2026-11-10'
provider_name: usewire-io
provider_slug: usewire-io
slug: usewire-io-eligibility
source_date: '2026-11-10'
source_filename: usewire-io-eligibility.yml
source_heading: Eligibility
source_page: https://usewire.io/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: usewire-io\naid: usewire-io\nurl: https://usewire.io/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Wire uses globally distributed edge compute infrastructure, object storage, and serverless databases to\n    deliver these services worldwide.\nentity_types:\n- type: individual\n  text: You must be at least 13 years old to use Wire. If you are under 18, you must have permission from a parent\n    or legal guardian.\n- type: business\n  text: You may create or join organizations.\nrestricted_uses:\n- summary: Illegal content\n  text: Store or process illegal content, including\
  \ child exploitation material\n- summary: Cryptocurrency mining\n  text: Use the Services for cryptocurrency mining\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: To use Wire, you must create an account.\nminimum_age:\n  value: '13'\n  text: You must be at least 13 years old to use Wire.\n"
source_yaml_url: https://artifacts.apis.io/usewire-io/eligibility/usewire-io-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 7 quoted statements, read from usewire-io's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- MCP
- Collaboration
- Context
- Platform
---
