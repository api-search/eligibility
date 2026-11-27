---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: if you are acting as a consumer, for your personal use only
    type: individual
  - text: if you are acting in the course of your employment or business
    type: business
  minimum_age:
    text: be at least 18 years old
    value: '18'
  restricted_uses:
  - summary: No access beyond assigned Digital Identity
    text: You shall not attempt, directly or indirectly, to gain access to any restricted part of the Offr Service which you are not entitled to access
  verification:
    approval_required: true
    kyb: null
    kyc: true
    text: carry out sufficient and risk-based due diligence checks on individual users as required under respective anti-money laundering and know your customer
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Offr
provenance_date: '2026-11-10'
provider_name: Offr
provider_slug: offr
slug: offr-eligibility
source_date: '2026-11-10'
source_filename: offr-eligibility.yml
source_heading: Eligibility
source_page: https://offr.io/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Offr\naid: offr\nurl: https://offr.io/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: if you are acting as a consumer, for your personal use only\n- type: business\n  text: if you are acting in the course of your employment or business\nrestricted_uses:\n- summary: No access beyond assigned Digital Identity\n  text: You shall not attempt, directly or indirectly, to gain access to any restricted part of the Offr Service\n    which you are not entitled to access\nverification:\n  kyc: true\n  kyb:\
  \ null\n  approval_required: true\n  text: carry out sufficient and risk-based due diligence checks on individual users as required under respective\n    anti-money laundering and know your customer\nminimum_age:\n  value: '18'\n  text: be at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/offr/eligibility/offr-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Offr's own page on 2026-11-10.
synthetic: false
tags:
- Company
- PropTech
- Real Estate
- Property Transactions
- Auctions
- Lettings
- Offer Management
- Ireland
---
