---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: “Customer” means the entity or person identified on the applicable Order Form.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No sensitive data as input
    text: provide sensitive data (e.g., health information, government IDs, financial data) as Customer Data or an Input
  - summary: No detrimental automated decisions
    text: make automated decisions that may have a detrimental impact on individual rights without appropriate human supervision
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
name: Revenue.io
provenance_date: '2026-11-10'
provider_name: Revenue.io
provider_slug: revenue-io
slug: revenue-io-eligibility
source_date: '2026-11-10'
source_filename: revenue-io-eligibility.yml
source_heading: Eligibility
source_page: https://www.revenue.io/msa
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Revenue.io\naid: revenue-io\nurl: https://www.revenue.io/msa\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: “Customer” means the entity or person identified on the applicable Order Form.\nrestricted_uses:\n- summary: No sensitive data as input\n  text: provide sensitive data (e.g., health information, government IDs, financial data) as Customer Data or an\n    Input\n- summary: No detrimental automated decisions\n  text: make automated decisions that may have a detrimental impact on individual rights without appropriate human\n    supervision\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/revenue-io/eligibility/revenue-io-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Revenue.io's own page on 2026-11-10.
synthetic: false
tags:
- Revenue Intelligence
- Sales Engagement
- Conversation Intelligence
- Revenue Operations
- Call Analytics
- Real-Time Guidance
- CRM Integration
- Salesforce
---
