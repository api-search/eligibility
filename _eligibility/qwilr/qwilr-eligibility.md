---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are using the Platform on behalf of your employer or a business entity, you, in your individual capacity, represent and warrant that you are authorised to act on behalf of your employer or the business entity
    type: business
  minimum_age:
    text: You and each Authorised User must be at least 16 years old to use the Platform.
    value: '16'
  restricted_uses:
  - summary: Legal use only
    text: You agree that you shall only use the Platform for legal purposes and shall not use it to engage in any conduct that is unlawful, immoral, threatening, abusive
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
name: Qwilr
provenance_date: '2026-11-10'
provider_name: Qwilr
provider_slug: qwilr
slug: qwilr-eligibility
source_date: '2026-11-10'
source_filename: qwilr-eligibility.yml
source_heading: Eligibility
source_page: https://qwilr.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Qwilr\naid: qwilr\nurl: https://qwilr.com/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are using the Platform on behalf of your employer or a business entity, you, in your individual capacity,\n    represent and warrant that you are authorised to act on behalf of your employer or the business entity\nrestricted_uses:\n- summary: Legal use only\n  text: You agree that you shall only use the Platform for legal purposes and shall not use it to engage in any\n    conduct that is unlawful, immoral, threatening, abusive\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: You and each Authorised User must be at least 16 years old to use the Platform.\n"
source_yaml_url: https://artifacts.apis.io/qwilr/eligibility/qwilr-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Qwilr's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Proposals
- Documents
- Sales
- Quotes
- Contracts
- E-Signature
- Webhook
- MCP
- Software-as-a-Service
---
