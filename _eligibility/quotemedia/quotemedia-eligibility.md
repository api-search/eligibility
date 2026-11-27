---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Our Service is provided exclusively for your personal, non-professional and noncommercial access and use.
    type: individual
  - text: You are subscribing on behalf of a firm, corporation, partnership, trust or association.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Non-professional use limit
    text: Subject to the provisions relating to Professional Users in Section H herein, Our Service is provided exclusively for your personal, non-professional and noncommercial access and use.
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
name: QuoteMedia
provenance_date: '2026-11-10'
provider_name: QuoteMedia
provider_slug: quotemedia
slug: quotemedia-eligibility
source_date: '2026-11-10'
source_filename: quotemedia-eligibility.yml
source_heading: Eligibility
source_page: https://quotemedia.com/legal/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: QuoteMedia\naid: quotemedia\nurl: https://quotemedia.com/legal/tos\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Our Service is provided exclusively for your personal, non-professional and noncommercial access and use.\n- type: business\n  text: You are subscribing on behalf of a firm, corporation, partnership, trust or association.\nrestricted_uses:\n- summary: Non-professional use limit\n  text: Subject to the provisions relating to Professional Users in Section H herein, Our Service is provided exclusively\n\
  \    for your personal, non-professional and noncommercial access and use.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/quotemedia/eligibility/quotemedia-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from QuoteMedia's own page on 2026-11-10.
synthetic: false
tags:
- Finance
- Market Data
- Stocks
- Options
- Real-Time
- Streaming
- News
- Fundamentals
- Reference Data
---
