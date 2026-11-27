---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You confirm that you are at least 18 years old and have the legal capacity to enter into these Terms.
    type: individual
  minimum_age:
    text: You confirm that you are at least 18 years old and have the legal capacity to enter into these Terms.
    value: '18'
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
name: Bliq
provenance_date: '2026-11-09'
provider_name: Bliq
provider_slug: bliq
slug: bliq-eligibility
source_date: '2026-11-09'
source_filename: bliq-eligibility.yml
source_heading: Eligibility
source_page: https://www.bliq.ai/toc
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bliq\naid: bliq\nurl: https://www.bliq.ai/toc\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You confirm that you are at least 18 years old and have the legal capacity to enter into these Terms.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You confirm that you are at least 18 years old and have the legal capacity to enter into these Terms.\n"
source_yaml_url: https://artifacts.apis.io/bliq/eligibility/bliq-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from Bliq's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Mobility
- Autonomous Vehicles
- Car Subscription
- Transportation
- Automotive
- Berlin
- Europe
---
