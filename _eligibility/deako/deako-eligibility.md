---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    - CA
    text: The Products are designed for use in the United States and Canada
  entity_types:
  - text: You represent and warrant that you are at least thirteen years of age, and have the right, authority, and capacity to accept and agree to these Terms.
    type: individual
  - text: Eligibility is limited to orders placed on Deako’s consumer website, shop.deako.com and is not extended to business to business transactions.
    type: business
  minimum_age:
    text: You represent and warrant that you are at least thirteen years of age
    value: '13'
  restricted_uses:
  - summary: Illegal purpose
    text: You may not use the Service for any illegal purpose.
  - summary: Commercial activities
    text: to engage in commercial activities of any kind.
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
name: Deako
provenance_date: '2026-11-09'
provider_name: Deako
provider_slug: deako
slug: deako-eligibility
source_date: '2026-11-09'
source_filename: deako-eligibility.yml
source_heading: Eligibility
source_page: https://www.deako.com/legal/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Deako\naid: deako\nurl: https://www.deako.com/legal/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  - CA\n  excluded: []\n  text: The Products are designed for use in the United States and Canada\nentity_types:\n- type: individual\n  text: You represent and warrant that you are at least thirteen years of age, and have the right, authority, and\n    capacity to accept and agree to these Terms.\n- type: business\n  text: Eligibility is limited to orders placed on Deako’s consumer website, shop.deako.com and is not extended\n    to business to business transactions.\nrestricted_uses:\n\
  - summary: Illegal purpose\n  text: You may not use the Service for any illegal purpose.\n- summary: Commercial activities\n  text: to engage in commercial activities of any kind.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You represent and warrant that you are at least thirteen years of age\n"
source_yaml_url: https://artifacts.apis.io/deako/eligibility/deako-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from Deako's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Industrial, Energy & Iot
- Smart Home
- Smart Lighting
- Home Automation
- IoT
- Lighting
- Matter
---
