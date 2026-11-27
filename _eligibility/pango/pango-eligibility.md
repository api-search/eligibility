---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least eighteen (18) years old to access and use the Service.
    type: individual
  - text: If you are entering into these Terms on behalf of an entity, you represent that you have the authority to bind that entity.
    type: business
  minimum_age:
    text: You must be at least eighteen (18) years old to access and use the Service.
    value: '18'
  restricted_uses:
  - summary: No allowing third parties to use the Service
    text: Allow any third party to use the Service.
  - summary: No processing data for third parties
    text: Use the Service to process data on behalf of any third party.
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
name: Pango
provenance_date: '2026-11-10'
provider_name: Pango
provider_slug: pango
slug: pango-eligibility
source_date: '2026-11-10'
source_filename: pango-eligibility.yml
source_heading: Eligibility
source_page: https://pango.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Pango\naid: pango\nurl: https://pango.ai/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least eighteen (18) years old to access and use the Service.\n- type: business\n  text: If you are entering into these Terms on behalf of an entity, you represent that you have the authority to\n    bind that entity.\nrestricted_uses:\n- summary: No allowing third parties to use the Service\n  text: Allow any third party to use the Service.\n- summary: No processing data for third parties\n  text: Use the Service to process\
  \ data on behalf of any third party.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least eighteen (18) years old to access and use the Service.\n"
source_yaml_url: https://artifacts.apis.io/pango/eligibility/pango-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Pango's own page on 2026-11-10.
synthetic: false
tags:
- Company
- E-Commerce
- Logistics
- Shipping
- Fulfillment
- Returns
- Order Tracking
- Artificial Intelligence
- Agents
- Y Combinator
---
