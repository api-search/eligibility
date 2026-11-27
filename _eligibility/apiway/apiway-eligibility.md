---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Business User — any User who is not a Consumer, including anyone who accepts these Terms on behalf of a company or other organization
    type: business
  - text: a natural person who uses the Service wholly or mainly for purposes outside that person’s trade, business, craft, or profession
    type: individual
  minimum_age:
    text: You must be at least sixteen (16) years old to create an account or use the Service.
    value: '16'
  restricted_uses:
  - summary: Deception, impersonation, regulated advice
    text: use AI features for deception, impersonation, passing off, unlawful deepfakes, biometric identification, unlawful profiling, or for medical, financial, legal, or other regulated advice without appropriate professional oversight
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
name: Apiway
provenance_date: '2026-11-09'
provider_name: Apiway
provider_slug: apiway
slug: apiway-eligibility
source_date: '2026-11-09'
source_filename: apiway-eligibility.yml
source_heading: Eligibility
source_page: https://apiway.ai/legal/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Apiway\naid: apiway\nurl: https://apiway.ai/legal/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Business User — any User who is not a Consumer, including anyone who accepts these Terms on behalf of a\n    company or other organization\n- type: individual\n  text: a natural person who uses the Service wholly or mainly for purposes outside that person’s trade, business,\n    craft, or profession\nrestricted_uses:\n- summary: Deception, impersonation, regulated advice\n  text: use AI features for deception,\
  \ impersonation, passing off, unlawful deepfakes, biometric identification,\n    unlawful profiling, or for medical, financial, legal, or other regulated advice without appropriate professional\n    oversight\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: You must be at least sixteen (16) years old to create an account or use the Service.\n"
source_yaml_url: https://artifacts.apis.io/apiway/eligibility/apiway-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Apiway's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Workspace
- Automation
- No-Code
---
