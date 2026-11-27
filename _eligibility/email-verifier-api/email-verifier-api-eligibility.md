---
api_specs:
- filename: email-verifier-api-verification-api-openapi.yml
  format: yaml
  label: Email Verifier API Verification API
  slug: email-verifier-api-verification-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/email-verifier-api/openapi/email-verifier-api-verification-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: By using Email Verifier API, you warrant that you meet this age requirement.
    type: individual
  minimum_age:
    text: You must be at least 18 years of age to use this service.
    value: '18'
  restricted_uses:
  - summary: Spam and harvesting
    text: You must not use our services in connection with sending unsolicited bulk commercial email (SPAM).
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
name: Email Verifier API
provenance_date: '2026-11-09'
provider_name: Email Verifier API
provider_slug: email-verifier-api
slug: email-verifier-api-eligibility
source_date: '2026-11-09'
source_filename: email-verifier-api-eligibility.yml
source_heading: Eligibility
source_page: https://emailverifierapi.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Email Verifier API\naid: email-verifier-api\nurl: https://emailverifierapi.com/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: By using Email Verifier API, you warrant that you meet this age requirement.\nrestricted_uses:\n- summary: Spam and harvesting\n  text: You must not use our services in connection with sending unsolicited bulk commercial email (SPAM).\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years of age\
  \ to use this service.\n"
source_yaml_url: https://artifacts.apis.io/email-verifier-api/eligibility/email-verifier-api-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Email Verifier API's own page on 2026-11-09.
synthetic: false
tags:
- Email Verification
- Deliverability
- SMTP Check
- Bounce Prevention
- Lead Validation
- Disposable Detection
- Spam Trap Detection
- Catch-All Detection
- Greylisting
- Role Account Detection
- Typo Suggestion
- B2B Lead Scoring
---
