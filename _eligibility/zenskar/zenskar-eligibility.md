---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: When you create an account with us, you guarantee that you are above the age of 18
    value: '18'
  restricted_uses:
  - summary: Prohibited uses of the Service
    text: 'You agree not to use Service: (a) In any way that violates any applicable national or international law or regulation.'
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
name: Zenskar
provenance_date: '2026-11-10'
provider_name: Zenskar
provider_slug: zenskar
slug: zenskar-eligibility
source_date: '2026-11-10'
source_filename: zenskar-eligibility.yml
source_heading: Eligibility
source_page: https://www.zenskar.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Zenskar\naid: zenskar\nurl: https://www.zenskar.com/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Prohibited uses of the Service\n  text: 'You agree not to use Service: (a) In any way that violates any applicable national or international law\n    or regulation.'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: When you create an account with us, you guarantee that you are above the age of 18\n"
source_yaml_url: https://artifacts.apis.io/zenskar/eligibility/zenskar-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Zenskar's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Cloud
- Billing
- Usage-Based Billing
- Revenue Automation
- Subscription Management
- Revenue Recognition
- Invoicing
- Fintech
- Order-to-Cash
- MCP
---
