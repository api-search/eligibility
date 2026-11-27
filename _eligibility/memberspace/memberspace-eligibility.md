---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: if you are entering into an agreement with us on behalf of an entity, that you are authorized to bind such entity in legal obligations
    type: business
  minimum_age:
    text: you represent that you are above the age of 18
    value: '18'
  restricted_uses:
  - summary: No Sensitive Personal Information
    text: You specifically agree not to use the Services to collect, store, process or transmit any Sensitive Personal Information.
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
name: MemberSpace
provenance_date: '2026-11-10'
provider_name: MemberSpace
provider_slug: memberspace
slug: memberspace-eligibility
source_date: '2026-11-10'
source_filename: memberspace-eligibility.yml
source_heading: Eligibility
source_page: https://www.memberspace.com/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: MemberSpace\naid: memberspace\nurl: https://www.memberspace.com/terms-and-conditions/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: if you are entering into an agreement with us on behalf of an entity, that you are authorized to bind such\n    entity in legal obligations\nrestricted_uses:\n- summary: No Sensitive Personal Information\n  text: You specifically agree not to use the Services to collect, store, process or transmit any Sensitive Personal\n    Information.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n\
  \  text: null\nminimum_age:\n  value: '18'\n  text: you represent that you are above the age of 18\n"
source_yaml_url: https://artifacts.apis.io/memberspace/eligibility/memberspace-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from MemberSpace's own page on 2026-11-10.
synthetic: false
tags:
- Software-as-a-Service
- Membership
- Payments
- Community
- Integration
- Company
---
