---
api_specs:
- filename: mailprobe-dev-account-api-openapi.yml
  format: yaml
  label: mailprobe-dev Account API
  slug: mailprobe-dev-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mailprobe-dev/openapi/mailprobe-dev-account-api-openapi.yml
- filename: mailprobe-dev-verification-api-openapi.yml
  format: yaml
  label: mailprobe-dev Verification API
  slug: mailprobe-dev-verification-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mailprobe-dev/openapi/mailprobe-dev-verification-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: One account per person or organization.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Spam, phishing, illegal activity
    text: Use the service for spamming, phishing, or any illegal activity.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You must provide a valid email address to create an account.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: mailprobe-dev
provenance_date: '2026-11-10'
provider_name: mailprobe-dev
provider_slug: mailprobe-dev
slug: mailprobe-dev-eligibility
source_date: '2026-11-10'
source_filename: mailprobe-dev-eligibility.yml
source_heading: Eligibility
source_page: https://mailprobe.dev/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: mailprobe-dev\naid: mailprobe-dev\nurl: https://mailprobe.dev/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: One account per person or organization.\nrestricted_uses:\n- summary: Spam, phishing, illegal activity\n  text: Use the service for spamming, phishing, or any illegal activity.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You must provide a valid email address to create an account.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/mailprobe-dev/eligibility/mailprobe-dev-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from mailprobe-dev's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Email Verification
- Real-Time
- Developer Tools
---
