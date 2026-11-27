---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: IF YOU ARE ENTERING INTO THIS AGREEMENT ON BEHALF OF A COMPANY OR ANOTHER LEGAL ENTITY, YOU REPRESENT THAT YOU HAVE THE AUTHORITY TO BIND SUCH ENTITY
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No FCRA eligibility determinations
    text: Customer hereby certifies that it will not use the Service or Product Data to determine, in whole or in part, an individual’s eligibility for any of the following products, services or transactions
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
name: Deduce
provenance_date: '2026-11-09'
provider_name: Deduce
provider_slug: deduce-ai
slug: deduce-ai-eligibility
source_date: '2026-11-09'
source_filename: deduce-ai-eligibility.yml
source_heading: Eligibility
source_page: https://cheq.ai/deduce-terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Deduce\naid: deduce-ai\nurl: https://cheq.ai/deduce-terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: IF YOU ARE ENTERING INTO THIS AGREEMENT ON BEHALF OF A COMPANY OR ANOTHER LEGAL ENTITY, YOU REPRESENT THAT\n    YOU HAVE THE AUTHORITY TO BIND SUCH ENTITY\nrestricted_uses:\n- summary: No FCRA eligibility determinations\n  text: Customer hereby certifies that it will not use the Service or Product Data to determine, in whole or in\n    part, an individual’s eligibility for any of the following products, services or transactions\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/deduce-ai/eligibility/deduce-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Deduce's own page on 2026-11-09.
synthetic: false
tags:
- Identity
- Fraud Prevention
- Risk Scoring
- Synthetic Identity
- Account Takeover
- New Account Fraud
- Checkout Fraud
- Identity Graph
- Artificial Intelligence
- GenAI Fraud
- KYC
- Onboarding
- Banking
- Fintech
- Payments
---
