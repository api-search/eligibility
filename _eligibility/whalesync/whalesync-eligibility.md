---
api_specs:
- filename: whalesync-openapi-generated.yml
  format: yaml
  label: Whalesync API
  slug: whalesync-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/whalesync/openapi/_ae-authored/whalesync-openapi-generated.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Services are business tools intended for commercial use by users who are at least 18 years old.
    type: business
  minimum_age:
    text: intended for commercial use by users who are at least 18 years old
    value: '18'
  restricted_uses:
  - summary: Protected Health Information
    text: You may not use the Services to create, receive, maintain, or transmit Protected Health Information ("PHI") as defined under HIPAA unless (a) you and Whalesync have executed a Business Associate Agreement
  - summary: Biometric data
    text: You may not submit to the Services, or configure a sync to transmit, any biometric identifier or biometric information
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
name: Whalesync
provenance_date: '2026-11-10'
provider_name: Whalesync
provider_slug: whalesync
slug: whalesync-eligibility
source_date: '2026-11-10'
source_filename: whalesync-eligibility.yml
source_heading: Eligibility
source_page: https://www.whalesync.com/company/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Whalesync\naid: whalesync\nurl: https://www.whalesync.com/company/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The Services are business tools intended for commercial use by users who are at least 18 years old.\nrestricted_uses:\n- summary: Protected Health Information\n  text: You may not use the Services to create, receive, maintain, or transmit Protected Health Information (\"PHI\")\n    as defined under HIPAA unless (a) you and Whalesync have executed a Business Associate Agreement\n- summary: Biometric data\n\
  \  text: You may not submit to the Services, or configure a sync to transmit, any biometric identifier or biometric\n    information\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: intended for commercial use by users who are at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/whalesync/eligibility/whalesync-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Whalesync's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Integration
- Data Sync
- No-Code
- Software-as-a-Service
---
