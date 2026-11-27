---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If acting on behalf of a legal entity, the User declares that they may not share the account and that they have the necessary authority to execute all available actions on behalf of that User on the Platform
    type: business
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: The User authorizes Mundi, directly or through third parties, to conduct inquiries or investigations to verify their identity, information provided, and other financial information
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Mundi
provenance_date: '2026-11-10'
provider_name: Mundi
provider_slug: mundi
slug: mundi-eligibility
source_date: '2026-11-10'
source_filename: mundi-eligibility.yml
source_heading: Eligibility
source_page: https://mundi.io/en/legal/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Mundi\naid: mundi\nurl: https://mundi.io/en/legal/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If acting on behalf of a legal entity, the User declares that they may not share the account and that they\n    have the necessary authority to execute all available actions on behalf of that User on the Platform\nrestricted_uses: []\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: The User authorizes Mundi, directly or through third parties, to conduct inquiries or investigations to\n   \
  \ verify their identity, information provided, and other financial information\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/mundi/eligibility/mundi-eligibility.yml
stated_fields:
- entity_types
- verification
summary_line: 2 quoted statements, read from Mundi's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Financial Services
- Trade Finance
- Fintech
- Factoring
- Payments
- Foreign Exchange
- Cargo Insurance
- Cross-Border Trade
- Mexico
---
