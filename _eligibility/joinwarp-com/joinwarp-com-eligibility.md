---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Employer must link at least one United States-based bank account to facilitate payment processing and Service Fee collection, unless otherwise authorized by Warp in writing.
  entity_types:
  - text: '"Employer" refers to the business entity, organization, or company on whose behalf this Agreement is accepted.'
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: High-risk industries prohibited
    text: 'Warp prohibits the provision of Services to businesses operating in certain high-risk industries, including but not limited to: adult entertainment, cannabis-related businesses, cryptocurrency, multi-level marketing, gambling, firearms manufacturing or sales, tobacco or vaping, alternative financial services, political campaigns, debt collection, precious metals dealers, and affiliate marketing-based businesses.'
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
name: Warp
provenance_date: '2026-11-09'
provider_name: Warp
provider_slug: joinwarp-com
slug: joinwarp-com-eligibility
source_date: '2026-11-09'
source_filename: joinwarp-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.warp.co/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Warp\naid: joinwarp-com\nurl: https://www.warp.co/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Employer must link at least one United States-based bank account to facilitate payment processing and Service\n    Fee collection, unless otherwise authorized by Warp in writing.\nentity_types:\n- type: business\n  text: '\"Employer\" refers to the business entity, organization, or company on whose behalf this Agreement is accepted.'\nrestricted_uses:\n- summary: High-risk industries prohibited\n  text: 'Warp prohibits the provision of Services to businesses operating in\
  \ certain high-risk industries, including\n    but not limited to: adult entertainment, cannabis-related businesses, cryptocurrency, multi-level marketing,\n    gambling, firearms manufacturing or sales, tobacco or vaping, alternative financial services, political campaigns,\n    debt collection, precious metals dealers, and affiliate marketing-based businesses.'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/joinwarp-com/eligibility/joinwarp-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Warp's own page on 2026-11-09.
synthetic: false
tags:
- Payroll
- Benefits
- Tax Compliance
- IT Management
- Global Payroll
- HRIS
- AI Agents
---
