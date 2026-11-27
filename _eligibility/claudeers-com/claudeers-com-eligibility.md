---
api_specs:
- filename: claudeers-com-openapi-generated.yml
  format: yaml
  label: Claudeers API
  slug: claudeers-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/claudeers-com/openapi/_ae-authored/claudeers-com-openapi-generated.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 13 (or the minimum age in your jurisdiction) and able to form a binding contract.
    type: individual
  minimum_age:
    text: You must be at least 13 (or the minimum age in your jurisdiction) and able to form a binding contract.
    value: '13'
  restricted_uses:
  - summary: Violating AI usage standards
    text: list or promote a project whose primary purpose violates applicable AI usage standards — including Anthropic's Usage Policy where Claude is involved
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Accounts are created via GitHub sign-in.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Claudeers
provenance_date: '2026-11-09'
provider_name: Claudeers
provider_slug: claudeers-com
slug: claudeers-com-eligibility
source_date: '2026-11-09'
source_filename: claudeers-com-eligibility.yml
source_heading: Eligibility
source_page: https://claudeers.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Claudeers\naid: claudeers-com\nurl: https://claudeers.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 13 (or the minimum age in your jurisdiction) and able to form a binding contract.\nrestricted_uses:\n- summary: Violating AI usage standards\n  text: list or promote a project whose primary purpose violates applicable AI usage standards — including Anthropic's\n    Usage Policy where Claude is involved\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Accounts are created via\
  \ GitHub sign-in.\nminimum_age:\n  value: '13'\n  text: You must be at least 13 (or the minimum age in your jurisdiction) and able to form a binding contract.\n"
source_yaml_url: https://artifacts.apis.io/claudeers-com/eligibility/claudeers-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Claudeers's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Registry
- Community
- Project
- Claude
---
