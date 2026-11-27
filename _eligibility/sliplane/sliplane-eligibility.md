---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 'If you''re signing up on behalf of a company, organization, or other legal entity, you confirm that: You have the authority to legally bind that entity to these terms'
    type: business
  - text: If you are a consumer (as defined under applicable consumer protection laws), you have the right to withdraw from this contract within 14 days of contract conclusion without providing any reason.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export controls and sanctions
    text: You're not located in or a resident of any country under U.S. or EU embargo
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
name: Sliplane
provenance_date: '2026-11-10'
provider_name: Sliplane
provider_slug: sliplane
slug: sliplane-eligibility
source_date: '2026-11-10'
source_filename: sliplane-eligibility.yml
source_heading: Eligibility
source_page: https://sliplane.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Sliplane\naid: sliplane\nurl: https://sliplane.io/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: 'If you''re signing up on behalf of a company, organization, or other legal entity, you confirm that: You\n    have the authority to legally bind that entity to these terms'\n- type: individual\n  text: If you are a consumer (as defined under applicable consumer protection laws), you have the right to withdraw\n    from this contract within 14 days of contract conclusion without providing any reason.\nrestricted_uses:\n- summary: Export\
  \ controls and sanctions\n  text: You're not located in or a resident of any country under U.S. or EU embargo\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/sliplane/eligibility/sliplane-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Sliplane's own page on 2026-11-10.
synthetic: false
tags:
- Container Hosting
- Docker Hosting
- Container As A Service
- Platform-as-a-Service
- Push To Deploy
- Cloud Infrastructure
- European Cloud
- Germany
- Developer Tools
- DevOps
- MCP
---
