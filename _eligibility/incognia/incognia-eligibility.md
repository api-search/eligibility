---
api_specs:
- filename: incognia-authentication-api-openapi.yml
  format: yaml
  label: Incognia Authentication API
  slug: incognia-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/incognia/openapi/incognia-authentication-api-openapi.yml
- filename: incognia-feedback-api-openapi.yml
  format: yaml
  label: Incognia Feedback API
  slug: incognia-feedback-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/incognia/openapi/incognia-feedback-api-openapi.yml
- filename: incognia-onboarding-api-openapi.yml
  format: yaml
  label: Incognia Onboarding API
  slug: incognia-onboarding-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/incognia/openapi/incognia-onboarding-api-openapi.yml
- filename: incognia-transactions-api-openapi.yml
  format: yaml
  label: Incognia Transactions API
  slug: incognia-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/incognia/openapi/incognia-transactions-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: entered into by and between Incognia US Inc. (" Incognia ") and the counterparty (“ Client ”) identified in an order form
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Fraudulent or illegal activities
    text: (C) Client is using the Services for fraudulent or illegal activities
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
name: Incognia
provenance_date: '2026-11-09'
provider_name: Incognia
provider_slug: incognia
slug: incognia-eligibility
source_date: '2026-11-09'
source_filename: incognia-eligibility.yml
source_heading: Eligibility
source_page: https://www.incognia.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Incognia\naid: incognia\nurl: https://www.incognia.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: entered into by and between Incognia US Inc. (\" Incognia \") and the counterparty (“ Client ”) identified\n    in an order form\nrestricted_uses:\n- summary: Fraudulent or illegal activities\n  text: (C) Client is using the Services for fraudulent or illegal activities\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/incognia/eligibility/incognia-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Incognia's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Cybersecurity
- Fraud Prevention
- Device Fingerprinting
- Location Identity
- Identity Verification
- Risk Assessment
- Authentication
- Fintech
---
