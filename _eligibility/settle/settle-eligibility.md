---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You understand that only corporations, limited liability companies(and no other type of business entities or sole proprietorships) validly organized under applicable law are able to use any lending services we provide
    type: business
  minimum_age:
    text: all Authorized Users are at least 18 years of age
    value: '18'
  restricted_uses:
  - summary: Business purposes only
    text: You further represent and warrant that you will access and use all Service for business purposes only and not for personal, family, or household purposes.
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: You authorize Settle, directly or through third parties, to make any inquiries we consider necessary to verify your or your business’ identity.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Settle
provenance_date: '2026-11-10'
provider_name: Settle
provider_slug: settle
slug: settle-eligibility
source_date: '2026-11-10'
source_filename: settle-eligibility.yml
source_heading: Eligibility
source_page: https://app.settle.co/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Settle\naid: settle\nurl: https://app.settle.co/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: You understand that only corporations, limited liability companies(and no other type of business entities\n    or sole proprietorships) validly organized under applicable law are able to use any lending services we provide\nrestricted_uses:\n- summary: Business purposes only\n  text: You further represent and warrant that you will access and use all Service for business purposes only and\n    not for personal,\
  \ family, or household purposes.\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: You authorize Settle, directly or through third parties, to make any inquiries we consider necessary to\n    verify your or your business’ identity.\nminimum_age:\n  value: '18'\n  text: all Authorized Users are at least 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/settle/eligibility/settle-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Settle's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fintech
- Payments
- Accounts Payable
- Procurement
- Working Capital
- Bill Pay
- Consumer Packaged Goods
- E-Commerce
- Financing
---
