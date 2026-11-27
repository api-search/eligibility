---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You may only create one account per person.
    type: individual
  minimum_age:
    text: You must be at least 18 years old to use the Service.
    value: '18'
  restricted_uses:
  - summary: No accounts for others without consent
    text: not create accounts on behalf of other people without their explicit written consent
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
name: SafeShepherd
provenance_date: '2026-11-10'
provider_name: SafeShepherd
provider_slug: safeshepherd
slug: safeshepherd-eligibility
source_date: '2026-11-10'
source_filename: safeshepherd-eligibility.yml
source_heading: Eligibility
source_page: https://safeshepherd.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: SafeShepherd\naid: safeshepherd\nurl: https://safeshepherd.com/legal/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You may only create one account per person.\nrestricted_uses:\n- summary: No accounts for others without consent\n  text: not create accounts on behalf of other people without their explicit written consent\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/safeshepherd/eligibility/safeshepherd-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from SafeShepherd's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Privacy
- Identity Protection
- Data Removal
- Data Brokers
- Consumer Security
- Personal Information
---
