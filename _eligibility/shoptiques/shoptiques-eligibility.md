---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: you represent that you are of legal age to form a binding contract
    type: individual
  minimum_age:
    text: you represent that you are of legal age to form a binding contract
    value: legal age to form a binding contract
  restricted_uses:
  - summary: One active account only
    text: Users may not have more than one active account.
  - summary: No transfer of accounts
    text: users are prohibited from selling, trading, or otherwise transferring your Shoptiques.com account to another party.
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
name: Shoptiques
provenance_date: '2026-11-10'
provider_name: Shoptiques
provider_slug: shoptiques
slug: shoptiques-eligibility
source_date: '2026-11-10'
source_filename: shoptiques-eligibility.yml
source_heading: Eligibility
source_page: https://shoptiques.com/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Shoptiques\naid: shoptiques\nurl: https://shoptiques.com/policies/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: you represent that you are of legal age to form a binding contract\nrestricted_uses:\n- summary: One active account only\n  text: Users may not have more than one active account.\n- summary: No transfer of accounts\n  text: users are prohibited from selling, trading, or otherwise transferring your Shoptiques.com account to another\n    party.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: legal age to form a binding contract\n  text: you represent that you are of legal age to form a binding contract\n"
source_yaml_url: https://artifacts.apis.io/shoptiques/eligibility/shoptiques-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Shoptiques's own page on 2026-11-10.
synthetic: false
tags:
- Company
- E-Commerce
- Retail
- Marketplace
- Boutiques
- Fashion
- Agentic Commerce
- Shopify
- MCP
- Universal Commerce Protocol
---
