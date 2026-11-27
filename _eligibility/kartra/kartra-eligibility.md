---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least eighteen years old to access any KARTRA Sites.
    type: individual
  - text: Client also agrees that if Client is ordering or purchasing Products or services on behalf of a company or other entity, that Client has proper authority to commit that company in such a transaction.
    type: business
  minimum_age:
    text: You must be at least eighteen years old to access any KARTRA Sites.
    value: '18'
  restricted_uses:
  - summary: Acceptable use restrictions
    text: Kartra may not be used to promote, market, exchange, store or produce offensive, illegal, harassing activities, or business that is likely to be flagged by spam agencies/filters.
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
name: Kartra
provenance_date: '2026-11-09'
provider_name: Kartra
provider_slug: kartra
slug: kartra-eligibility
source_date: '2026-11-09'
source_filename: kartra-eligibility.yml
source_heading: Eligibility
source_page: https://kartra.com/terms-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Kartra\naid: kartra\nurl: https://kartra.com/terms-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least eighteen years old to access any KARTRA Sites.\n- type: business\n  text: Client also agrees that if Client is ordering or purchasing Products or services on behalf of a company\n    or other entity, that Client has proper authority to commit that company in such a transaction.\nrestricted_uses:\n- summary: Acceptable use restrictions\n  text: Kartra may not be used to promote, market,\
  \ exchange, store or produce offensive, illegal, harassing activities,\n    or business that is likely to be flagged by spam agencies/filters.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least eighteen years old to access any KARTRA Sites.\n"
source_yaml_url: https://artifacts.apis.io/kartra/eligibility/kartra-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Kartra's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Marketing Automation
- Email Marketing
- CRM
- Contacts
- E-Commerce
- Payments
- Subscription
- Membership
- Landing Pages
- Webhook
- Software-as-a-Service
---
