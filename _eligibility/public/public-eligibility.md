---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Service is intended for visitors located within the United States. We make no representation that the Service is appropriate or available for use outside of the United States. Access to the Service from countries or territories or by individuals where such access is illegal is prohibited.
  entity_types:
  - text: You must be at least 18 years old to use the Services.
    type: individual
  minimum_age:
    text: You must be at least 18 years old to use the Services.
    value: '18'
  restricted_uses:
  - summary: Illegal or fraudulent use
    text: use the Services for any illegal purpose or violate any applicable federal, state, local, national, or international laws or regulations, or these Terms
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
name: Public
provenance_date: '2026-11-10'
provider_name: Public
provider_slug: public
slug: public-eligibility
source_date: '2026-11-10'
source_filename: public-eligibility.yml
source_heading: Eligibility
source_page: https://public.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Public\naid: public\nurl: https://public.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Service is intended for visitors located within the United States. We make no representation that the\n    Service is appropriate or available for use outside of the United States. Access to the Service from countries\n    or territories or by individuals where such access is illegal is prohibited.\nentity_types:\n- type: individual\n  text: You must be at least 18 years old to use the Services.\nrestricted_uses:\n- summary: Illegal or fraudulent\
  \ use\n  text: use the Services for any illegal purpose or violate any applicable federal, state, local, national, or international\n    laws or regulations, or these Terms\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to use the Services.\n"
source_yaml_url: https://artifacts.apis.io/public/eligibility/public-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Public's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Consumer
- Investing
- Brokerage
- Trading
- Fintech
- Stocks
- Options
- Cryptocurrency
- Market Data
- AI Agents
- MCP
- Financial Services
---
