---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You may use the Site only if you are 18 years or older and capable of forming a binding contract with PointOne
    type: individual
  - text: If you are accessing and using the Site on behalf of a company (such as your employer) or other legal entity, you represent and warrant that you have the authority to bind that entity to these Terms.
    type: business
  minimum_age:
    text: You may use the Site only if you are 18 years or older
    value: '18'
  restricted_uses:
  - summary: Non-professional use
    text: These services are intended for professional use within the legal industry and should not be used for personal or non-professional purposes.
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
name: Pointone
provenance_date: '2026-11-10'
provider_name: Pointone
provider_slug: pointone
slug: pointone-eligibility
source_date: '2026-11-10'
source_filename: pointone-eligibility.yml
source_heading: Eligibility
source_page: https://pointone.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Pointone\naid: pointone\nurl: https://pointone.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You may use the Site only if you are 18 years or older and capable of forming a binding contract with PointOne\n- type: business\n  text: If you are accessing and using the Site on behalf of a company (such as your employer) or other legal entity,\n    you represent and warrant that you have the authority to bind that entity to these Terms.\nrestricted_uses:\n- summary: Non-professional use\n  text: These services are intended for\
  \ professional use within the legal industry and should not be used for personal\n    or non-professional purposes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You may use the Site only if you are 18 years or older\n"
source_yaml_url: https://artifacts.apis.io/pointone/eligibility/pointone-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Pointone's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Legal
- Legal Tech
- Practice Management
- Time Tracking
- Billing
- Compliance
- Artificial Intelligence
- Law Firms
---
