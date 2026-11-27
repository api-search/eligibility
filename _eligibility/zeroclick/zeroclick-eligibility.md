---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: The Services must not be used by, or integrated with offerings directed to, anyone under the age of eighteen (18) or the age of majority where they reside.
    value: '18'
  restricted_uses:
  - summary: No use by minors
    text: The Services must not be used by, or integrated with offerings directed to, anyone under the age of eighteen (18) or the age of majority where they reside.
  verification:
    approval_required: true
    kyb: true
    kyc: null
    text: ZeroClick may require Seller, and Seller’s principals and beneficial owners, to provide information and documentation reasonably necessary for ZeroClick to verify Seller’s identity and to carry out sanctions, fraud and other compliance screening
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Zeroclick
provenance_date: '2026-11-10'
provider_name: Zeroclick
provider_slug: zeroclick
slug: zeroclick-eligibility
source_date: '2026-11-10'
source_filename: zeroclick-eligibility.yml
source_heading: Eligibility
source_page: https://zeroclick.ai/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Zeroclick\naid: zeroclick\nurl: https://zeroclick.ai/legal/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: No use by minors\n  text: The Services must not be used by, or integrated with offerings directed to, anyone under the age of eighteen\n    (18) or the age of majority where they reside.\nverification:\n  kyc: null\n  kyb: true\n  approval_required: true\n  text: ZeroClick may require Seller, and Seller’s principals and beneficial owners, to provide information and\n    documentation reasonably\
  \ necessary for ZeroClick to verify Seller’s identity and to carry out sanctions, fraud\n    and other compliance screening\nminimum_age:\n  value: '18'\n  text: The Services must not be used by, or integrated with offerings directed to, anyone under the age of eighteen\n    (18) or the age of majority where they reside.\n"
source_yaml_url: https://artifacts.apis.io/zeroclick/eligibility/zeroclick-eligibility.yml
stated_fields:
- restricted_uses
- verification
- minimum_age
summary_line: 3 quoted statements, read from Zeroclick's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Agentic Commerce
- Agentic Payments
- API Monetization
- x402
- Machine Payments Protocol
- Agent Identity
- Stripe
---
