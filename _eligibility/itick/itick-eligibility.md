---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you accept these Terms on behalf of a legal entity (including a business or government agency), you represent and warrant that you have the full legal authority to bind that entity to these Terms.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Violating laws or misuse
    text: Use the Site in any manner that violates applicable laws or regulations.
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
name: iTick
provenance_date: '2026-11-09'
provider_name: iTick
provider_slug: itick
slug: itick-eligibility
source_date: '2026-11-09'
source_filename: itick-eligibility.yml
source_heading: Eligibility
source_page: https://itick.org/en/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: iTick\naid: itick\nurl: https://itick.org/en/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you accept these Terms on behalf of a legal entity (including a business or government agency), you represent\n    and warrant that you have the full legal authority to bind that entity to these Terms.\nrestricted_uses:\n- summary: Violating laws or misuse\n  text: Use the Site in any manner that violates applicable laws or regulations.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/itick/eligibility/itick-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from iTick's own page on 2026-11-09.
synthetic: false
tags:
- Financial Data
- Market Data
- Stocks
- Foreign Exchange
- Cryptocurrency
- Indices
- Futures
- Fund
- Real-Time Data
- WebSocket
- FIX Protocol
- Fintech
- Quantitative Trading
- MCP Server
---
