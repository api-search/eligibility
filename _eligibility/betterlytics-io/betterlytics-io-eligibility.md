---
api_specs:
- filename: betterlytics-io-openapi-generated.yml
  format: yaml
  label: Betterlytics API
  slug: betterlytics-io-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/betterlytics-io/openapi/_ae-authored/betterlytics-io-openapi-generated.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old to use our service. If you are between 13-17, you may use our service only with parental consent.
    type: individual
  minimum_age:
    text: You must be at least 18 years old to use our service. If you are between 13-17, you may use our service only with parental consent.
    value: '18'
  restricted_uses:
  - summary: Illegal purposes
    text: You may not use our service for any illegal purpose or to violate any laws in your jurisdiction.
  - summary: Tracking without consent or lawful basis
    text: Track visitors without their knowledge or in violation of privacy laws
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You must provide a valid email address to complete the signup process. You must be a human - accounts registered by bots or automated methods are not permitted.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Betterlytics
provenance_date: '2026-11-09'
provider_name: Betterlytics
provider_slug: betterlytics-io
slug: betterlytics-io-eligibility
source_date: '2026-11-09'
source_filename: betterlytics-io-eligibility.yml
source_heading: Eligibility
source_page: https://betterlytics.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Betterlytics\naid: betterlytics-io\nurl: https://betterlytics.io/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old to use our service. If you are between 13-17, you may use our service\n    only with parental consent.\nrestricted_uses:\n- summary: Illegal purposes\n  text: You may not use our service for any illegal purpose or to violate any laws in your jurisdiction.\n- summary: Tracking without consent or lawful basis\n  text: Track visitors without their knowledge or in violation of privacy\
  \ laws\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You must provide a valid email address to complete the signup process. You must be a human - accounts registered\n    by bots or automated methods are not permitted.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to use our service. If you are between 13-17, you may use our service\n    only with parental consent.\n"
source_yaml_url: https://artifacts.apis.io/betterlytics-io/eligibility/betterlytics-io-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Betterlytics's own page on 2026-11-09.
synthetic: false
tags:
- Analytics
- Session Replay
- Error Tracking
- Core Web Vitals
- Uptime Monitoring
- Open Source
---
