---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 16 to use StackYard, and 18 to create a vendor account or make payments.
    type: individual
  - text: If you use StackYard for a company, you confirm you can bind that company, and “you” includes it.
    type: business
  minimum_age:
    text: You must be at least 16 to use StackYard, and 18 to create a vendor account or make payments.
    value: '16'
  restricted_uses:
  - summary: Buyer details limited to demo follow-up
    text: You may use a buyer’s details only to respond to their demo request and related follow-up
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
name: StackYard
provenance_date: '2026-11-10'
provider_name: StackYard
provider_slug: stackyard
slug: stackyard-eligibility
source_date: '2026-11-10'
source_filename: stackyard-eligibility.yml
source_heading: Eligibility
source_page: https://stackyard.ai/legal
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: StackYard\naid: stackyard\nurl: https://stackyard.ai/legal\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 16 to use StackYard, and 18 to create a vendor account or make payments.\n- type: business\n  text: If you use StackYard for a company, you confirm you can bind that company, and “you” includes it.\nrestricted_uses:\n- summary: Buyer details limited to demo follow-up\n  text: You may use a buyer’s details only to respond to their demo request and related follow-up\nverification:\n  kyc: null\n  kyb: null\n\
  \  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: You must be at least 16 to use StackYard, and 18 to create a vendor account or make payments.\n"
source_yaml_url: https://artifacts.apis.io/stackyard/eligibility/stackyard-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from StackYard's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Marketplace
- Directory
- Reviews
- AI Tools
---
