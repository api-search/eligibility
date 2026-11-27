---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: By you or your Authorized Users signing in with Google, Microsoft or SSO, or by accessing or using the Service, you acknowledge that you have read, understood, and agree to be bound by this TOS and affirm that you are over the age of 18.
    type: individual
  - text: If you are entering into this TOS on behalf of a business or other legal entity, you represent that you have the authority to bind the entity and its affiliates to this TOS
    type: business
  minimum_age:
    text: affirm that you are over the age of 18
    value: '18'
  restricted_uses:
  - summary: Sanctioned jurisdictions and restricted parties
    text: You represent, warrant and covenant that you are not (a) located in, or a resident or a national of, any country subject to a U.S. government embargo or other restriction
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
name: Warmly
provenance_date: '2026-11-10'
provider_name: Warmly
provider_slug: warmly
slug: warmly-eligibility
source_date: '2026-11-10'
source_filename: warmly-eligibility.yml
source_heading: Eligibility
source_page: https://www.warmly.ai/p/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Warmly\naid: warmly\nurl: https://www.warmly.ai/p/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: By you or your Authorized Users signing in with Google, Microsoft or SSO, or by accessing or using the Service,\n    you acknowledge that you have read, understood, and agree to be bound by this TOS and affirm that you are over\n    the age of 18.\n- type: business\n  text: If you are entering into this TOS on behalf of a business or other legal entity, you represent that you\n    have the authority to bind the entity\
  \ and its affiliates to this TOS\nrestricted_uses:\n- summary: Sanctioned jurisdictions and restricted parties\n  text: You represent, warrant and covenant that you are not (a) located in, or a resident or a national of, any\n    country subject to a U.S. government embargo or other restriction\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: affirm that you are over the age of 18\n"
source_yaml_url: https://artifacts.apis.io/warmly/eligibility/warmly-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Warmly's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Sales
- Marketing
- Intent Data
- Revenue Orchestration
- Website Visitor Identification
- AI Agents
- Go-To-Market
- MCP
- Lead Generation
- CRM
---
