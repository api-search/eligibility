---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years of age.
    type: individual
  minimum_age:
    text: You must be at least 18 years of age.
    value: '18'
  restricted_uses:
  - summary: Illegal or harmful use of profile
    text: Users shall refrain from using their profile and other Platform contents for illegal purposes or with illegal results that harm third-party rights and interests
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Zeew does not check (and is under no obligation to check) the identity of Users or the truthfulness, current validity, completeness, and/or authenticity of the data supplied by them.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Zeew
provenance_date: '2026-11-10'
provider_name: Zeew
provider_slug: zeew
slug: zeew-eligibility
source_date: '2026-11-10'
source_filename: zeew-eligibility.yml
source_heading: Eligibility
source_page: https://zeew.eu/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Zeew\naid: zeew\nurl: https://zeew.eu/terms-and-conditions/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years of age.\nrestricted_uses:\n- summary: Illegal or harmful use of profile\n  text: Users shall refrain from using their profile and other Platform contents for illegal purposes or with illegal\n    results that harm third-party rights and interests\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Zeew does not check (and is under no obligation to check) the identity of Users\
  \ or the truthfulness, current\n    validity, completeness, and/or authenticity of the data supplied by them.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years of age.\n"
source_yaml_url: https://artifacts.apis.io/zeew/eligibility/zeew-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Zeew's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Delivery
- On-Demand
- Food Delivery
- Logistics
- White Label
- Software-as-a-Service
- Marketplace
---
