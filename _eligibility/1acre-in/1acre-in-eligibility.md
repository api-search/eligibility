---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - IN
    text: Use of the Platform is restricted to individuals and entities legally competent to contract under Indian law.
  entity_types:
  - text: Users must be at least 18 years of age.
    type: individual
  - text: Developers Dashboard is strictly for professional use by developers, builders, institutional investors, funds, and corporate entities.
    type: business
  minimum_age:
    text: Users must be at least 18 years of age.
    value: '18'
  restricted_uses:
  - summary: Developers Dashboard professional use only
    text: The Developers Dashboard is strictly for professional use by developers, builders, institutional investors, funds, and corporate entities.
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
name: 1acre
provenance_date: '2026-11-09'
provider_name: 1acre
provider_slug: 1acre-in
slug: 1acre-in-eligibility
source_date: '2026-11-09'
source_filename: 1acre-in-eligibility.yml
source_heading: Eligibility
source_page: https://1acre.in/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: 1acre\naid: 1acre-in\nurl: https://1acre.in/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - IN\n  excluded: []\n  text: Use of the Platform is restricted to individuals and entities legally competent to contract under Indian\n    law.\nentity_types:\n- type: individual\n  text: Users must be at least 18 years of age.\n- type: business\n  text: Developers Dashboard is strictly for professional use by developers, builders, institutional investors,\n    funds, and corporate entities.\nrestricted_uses:\n- summary: Developers Dashboard professional use only\n  text: The Developers Dashboard\
  \ is strictly for professional use by developers, builders, institutional investors,\n    funds, and corporate entities.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Users must be at least 18 years of age.\n"
source_yaml_url: https://artifacts.apis.io/1acre-in/eligibility/1acre-in-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from 1acre's own page on 2026-11-09.
synthetic: false
tags:
- Real Estate
- LandMarketplace
- DataLayers
- India
- Developer Tools
---
