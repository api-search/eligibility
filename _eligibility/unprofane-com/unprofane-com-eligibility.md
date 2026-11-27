---
api_specs:
- filename: unprofane-com-api-openapi.json
  format: json
  label: Unprofane API API
  slug: unprofane-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unprofane-com/openapi/_original/unprofane-com-api-openapi.json
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Test keys not for serving users
    text: Test keys are for building and testing, not for serving a product's users.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: The Research plan is granted by application for studying text, not for serving a product's users;
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: unprofane-com
provenance_date: '2026-11-10'
provider_name: unprofane-com
provider_slug: unprofane-com
slug: unprofane-com-eligibility
source_date: '2026-11-10'
source_filename: unprofane-com-eligibility.yml
source_heading: Eligibility
source_page: https://unprofane.com/legal/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: unprofane-com\naid: unprofane-com\nurl: https://unprofane.com/legal/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Test keys not for serving users\n  text: Test keys are for building and testing, not for serving a product's users.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: The Research plan is granted by application for studying text, not for serving a product's users;\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/unprofane-com/eligibility/unprofane-com-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from unprofane-com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Profanity Filtering
- Content Moderation
- Machine Learning
- Safety
---
