---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Platform is currently available in the United States only.
  entity_types:
  - text: Customers — individuals who browse menus, place orders, and pay restaurants through the Platform.
    type: individual
  - text: Restaurant Owners — businesses that register to manage menus, receive orders, and process payments through the Platform.
    type: business
  minimum_age:
    text: null
    value: null
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
name: DirectTap
provenance_date: '2026-11-09'
provider_name: DirectTap
provider_slug: directtap
slug: directtap-eligibility
source_date: '2026-11-09'
source_filename: directtap-eligibility.yml
source_heading: Eligibility
source_page: https://directtap.ai/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: DirectTap\naid: directtap\nurl: https://directtap.ai/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Platform is currently available in the United States only.\nentity_types:\n- type: individual\n  text: Customers — individuals who browse menus, place orders, and pay restaurants through the Platform.\n- type: business\n  text: Restaurant Owners — businesses that register to manage menus, receive orders, and process payments through\n    the Platform.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\n\
  minimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/directtap/eligibility/directtap-eligibility.yml
stated_fields:
- countries
- entity_types
summary_line: 3 quoted statements, read from DirectTap's own page on 2026-11-09.
synthetic: false
tags:
- Restaurant
- Software-as-a-Service
- Marketplace
- Zero-Commission
- Ordering
---
