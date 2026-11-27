---
claim_count: 5
description: ''
doc:
  countries:
    excluded:
    - US
    - CA
    served:
    - ID
    text: Our Website is directed only to Indonesian residents. For the avoidance of doubt, the Website is not being offered in the US or Canada or to US persons or Canadian persons.
  entity_types:
  - text: You may only Use the Website if you are at least 18 years of age.
    type: individual
  minimum_age:
    text: You may only Use the Website if you are at least 18 years of age.
    value: '18'
  restricted_uses:
  - summary: Not investment advice
    text: The Service is not intended to provide tax, legal or investment advice, and nothing on the Service should be construed as an offer to sell, a solicitation of an offer to buy, or a recommendation for any security.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Upon our request, Registered Users and will provide to us proof of their identity and/or age.
excluded_countries:
- US
- CA
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Stockbit
provenance_date: '2026-11-10'
provider_name: Stockbit
provider_slug: stockbit
slug: stockbit-eligibility
source_date: '2026-11-10'
source_filename: stockbit-eligibility.yml
source_heading: Eligibility
source_page: https://stockbit.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Stockbit\naid: stockbit\nurl: https://stockbit.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - ID\n  excluded:\n  - US\n  - CA\n  text: Our Website is directed only to Indonesian residents. For the avoidance of doubt, the Website is not being\n    offered in the US or Canada or to US persons or Canadian persons.\nentity_types:\n- type: individual\n  text: You may only Use the Website if you are at least 18 years of age.\nrestricted_uses:\n- summary: Not investment advice\n  text: The Service is not intended to provide tax, legal or investment advice, and nothing on the Service should\n    be\
  \ construed as an offer to sell, a solicitation of an offer to buy, or a recommendation for any security.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Upon our request, Registered Users and will provide to us proof of their identity and/or age.\nminimum_age:\n  value: '18'\n  text: You may only Use the Website if you are at least 18 years of age.\n"
source_yaml_url: https://artifacts.apis.io/stockbit/eligibility/stockbit-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Stockbit's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fintech
- Investing
- Stock Trading
- Brokerage
- Indonesia
- Financial Services
- Cryptocurrency
---
