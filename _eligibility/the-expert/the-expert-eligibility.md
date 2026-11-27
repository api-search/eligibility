---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Expert Service is intended for users who reside in the United States of America.
  entity_types:
  - text: You affirm and represent and warrant that you are 18 years old or the age of majority in your jurisdiction
    type: individual
  - text: if you use The Expert Service and/or purchase any Products, Services, and/or Consultations on behalf of another person, or an entity, organization, or company, you represent and warrant that you have the authority to bind
    type: business
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: The Expert does not currently conduct any verification of or background checks on any Designers and/or Trade Vendors.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: The Expert
provenance_date: '2026-11-10'
provider_name: The Expert
provider_slug: the-expert
slug: the-expert-eligibility
source_date: '2026-11-10'
source_filename: the-expert-eligibility.yml
source_heading: Eligibility
source_page: https://www.theexpert.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: The Expert\naid: the-expert\nurl: https://www.theexpert.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Expert Service is intended for users who reside in the United States of America.\nentity_types:\n- type: individual\n  text: You affirm and represent and warrant that you are 18 years old or the age of majority in your jurisdiction\n- type: business\n  text: if you use The Expert Service and/or purchase any Products, Services, and/or Consultations on behalf of\n    another person, or an entity, organization, or company, you represent and warrant\
  \ that you have the authority\n    to bind\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: The Expert does not currently conduct any verification of or background checks on any Designers and/or Trade\n    Vendors.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/the-expert/eligibility/the-expert-eligibility.yml
stated_fields:
- countries
- entity_types
- verification
summary_line: 4 quoted statements, read from The Expert's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Consumer
- Interior Design
- Marketplace
- E-Commerce
- Home Design
- Video Consultations
---
