---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You represent and warrant that you are an individual of legal age to form a binding contract.
    type: individual
  minimum_age:
    text: You represent and warrant that you are an individual of legal age to form a binding contract.
    value: legal age
  restricted_uses:
  - summary: Circumventing Baton to close deals outside the Services
    text: attempts, in any manner, to circumvent the purpose of these Terms, including by creating an account for the purpose of identifying prospective Sellers or Buyers and pursuing or completing Sales outside the Services without payment to Baton
  - summary: Use in violation of law
    text: violates any law or regulation, including, without limitation, any applicable export control laws, or privacy laws
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
name: Baton Market
provenance_date: '2026-11-09'
provider_name: Baton Market
provider_slug: baton-market
slug: baton-market-eligibility
source_date: '2026-11-09'
source_filename: baton-market-eligibility.yml
source_heading: Eligibility
source_page: https://www.baton.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Baton Market\naid: baton-market\nurl: https://www.baton.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You represent and warrant that you are an individual of legal age to form a binding contract.\nrestricted_uses:\n- summary: Circumventing Baton to close deals outside the Services\n  text: attempts, in any manner, to circumvent the purpose of these Terms, including by creating an account for\n    the purpose of identifying prospective Sellers or Buyers and pursuing or completing Sales outside the\
  \ Services\n    without payment to Baton\n- summary: Use in violation of law\n  text: violates any law or regulation, including, without limitation, any applicable export control laws, or privacy\n    laws\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: legal age\n  text: You represent and warrant that you are an individual of legal age to form a binding contract.\n"
source_yaml_url: https://artifacts.apis.io/baton-market/eligibility/baton-market-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Baton Market's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Marketplace
- Business Brokerage
- Mergers and Acquisitions
- Small Business
- Business Valuation
- Business For Sale
- Deal Flow
---
