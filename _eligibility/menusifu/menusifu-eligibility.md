---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: ON BEHALF OF A COMPANY
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export restrictions
    text: You shall not permit Users to access
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
name: MenuSifu
provenance_date: '2026-11-10'
provider_name: MenuSifu
provider_slug: menusifu
slug: menusifu-eligibility
source_date: '2026-11-10'
source_filename: menusifu-eligibility.yml
source_heading: Eligibility
source_page: https://www.menusifu.com/master-services-agreement
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: MenuSifu\naid: menusifu\nurl: https://www.menusifu.com/master-services-agreement\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: ON BEHALF OF A COMPANY\nrestricted_uses:\n- summary: Export restrictions\n  text: You shall not permit Users to access\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/menusifu/eligibility/menusifu-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from MenuSifu's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Point-of-Sale
- Restaurant
- Restaurant Technology
- Hospitality
- Payments
- Online Ordering
- Loyalty
- Kitchen Display Systems
- Hardware
---
