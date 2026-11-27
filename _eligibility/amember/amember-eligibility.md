---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: BETWEEN YOU OR THE ENTITY THAT YOU REPRESENT
    type: business
  minimum_age:
    text: you are not of legal age or capacity to enter a contract in your jurisdiction, you are not authorized to use the Services
    value: null
  restricted_uses:
  - summary: Prohibited Uses
    text: (3) not violate any third party rights including but not limited to rights of privacy and intellectual property rights
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
name: aMember
provenance_date: '2026-11-09'
provider_name: aMember
provider_slug: amember
slug: amember-eligibility
source_date: '2026-11-09'
source_filename: amember-eligibility.yml
source_heading: Eligibility
source_page: https://www.amember.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: aMember\naid: amember\nurl: https://www.amember.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: BETWEEN YOU OR THE ENTITY THAT YOU REPRESENT\nrestricted_uses:\n- summary: Prohibited Uses\n  text: (3) not violate any third party rights including but not limited to rights of privacy and intellectual property\n    rights\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: you are not of legal age or capacity to enter a contract in your jurisdiction, you are not\
  \ authorized to\n    use the Services\n"
source_yaml_url: https://artifacts.apis.io/amember/eligibility/amember-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from aMember's own page on 2026-11-09.
synthetic: false
tags:
- Membership Software
- Subscription Management
- Self-Hosted
- Payment Integration
- Affiliate Program
- Team Accounts
---
