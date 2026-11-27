---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 'To use the Service, you represent and warrant that: you are at least 18 years of age'
    type: individual
  - text: If you are using the Service on behalf of a company or other entity, you represent and warrant that you have the authority to bind that entity to these Terms
    type: business
  minimum_age:
    text: you are at least 18 years of age
    value: '18'
  restricted_uses:
  - summary: Alcohol orders require age 21
    text: You may not order alcohol through the Service unless you and the intended recipient are at least 21 years of age.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: We may require you to provide information to verify your identity.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Zerocater
provenance_date: '2026-11-10'
provider_name: Zerocater
provider_slug: zerocater
slug: zerocater-eligibility
source_date: '2026-11-10'
source_filename: zerocater-eligibility.yml
source_heading: Eligibility
source_page: https://zerocater.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Zerocater\naid: zerocater\nurl: https://zerocater.com/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: 'To use the Service, you represent and warrant that: you are at least 18 years of age'\n- type: business\n  text: If you are using the Service on behalf of a company or other entity, you represent and warrant that you\n    have the authority to bind that entity to these Terms\nrestricted_uses:\n- summary: Alcohol orders require age 21\n  text: You may not order alcohol through the Service unless you and the intended recipient\
  \ are at least 21 years\n    of age.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: We may require you to provide information to verify your identity.\nminimum_age:\n  value: '18'\n  text: you are at least 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/zerocater/eligibility/zerocater-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Zerocater's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Food and Beverage
- Catering
- Corporate Services
- Workplace
- Food Delivery
- Hospitality
- Artificial Intelligence
- Ordering
- Marketplace
---
