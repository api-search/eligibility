---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: 'Apple-Enabled Software section: You represent and warrant that (i) you are not located in a country that is subject to a U.S. Government embargo'
  entity_types:
  - text: You are eligible to register for the Services only in your capacity as an individual and not in any other capacity, such as a sole proprietor, trustee, corporation, limited liability company, or any other corporate entity or association.
    type: individual
  minimum_age:
    text: If you are under 16 years of age, you are not authorized to use the Services, with or without registering.
    value: '16'
  restricted_uses:
  - summary: Under-age use
    text: If you are under 16 years of age, you are not authorized to use the Services, with or without registering.
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
name: Upside Services
provenance_date: '2026-11-10'
provider_name: Upside Services
provider_slug: upside-services
slug: upside-services-eligibility
source_date: '2026-11-10'
source_filename: upside-services-eligibility.yml
source_heading: Eligibility
source_page: https://www.upside.com/data-and-security/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Upside Services\naid: upside-services\nurl: https://www.upside.com/data-and-security/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: 'Apple-Enabled Software section: You represent and warrant that (i) you are not located in a country that\n    is subject to a U.S. Government embargo'\nentity_types:\n- type: individual\n  text: You are eligible to register for the Services only in your capacity as an individual and not in any other\n    capacity, such as a sole proprietor, trustee, corporation, limited liability company, or any other corporate\n    entity\
  \ or association.\nrestricted_uses:\n- summary: Under-age use\n  text: If you are under 16 years of age, you are not authorized to use the Services, with or without registering.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: If you are under 16 years of age, you are not authorized to use the Services, with or without registering.\n"
source_yaml_url: https://artifacts.apis.io/upside-services/eligibility/upside-services-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Upside Services's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Cashback
- Retail
- Fuel
- Grocery
- Restaurant
- Loyalty
- Consumer Incentives
---
