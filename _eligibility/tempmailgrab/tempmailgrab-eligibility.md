---
api_specs:
- filename: tempmailgrab-byod-api-openapi.yml
  format: yaml
  label: TempMailGrab API Byod API
  slug: tempmailgrab-byod-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tempmailgrab/openapi/tempmailgrab-byod-api-openapi.yml
- filename: tempmailgrab-inbox-api-openapi.yml
  format: yaml
  label: TempMailGrab API Inbox API
  slug: tempmailgrab-inbox-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tempmailgrab/openapi/tempmailgrab-inbox-api-openapi.yml
- filename: tempmailgrab-messages-api-openapi.yml
  format: yaml
  label: TempMailGrab API Messages API
  slug: tempmailgrab-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tempmailgrab/openapi/tempmailgrab-messages-api-openapi.yml
- filename: tempmailgrab-tempmailgrab-api-api-openapi.yml
  format: yaml
  label: TempMailGrab API TempMailGrab API
  slug: tempmailgrab-tempmailgrab-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tempmailgrab/openapi/tempmailgrab-tempmailgrab-api-api-openapi.yml
- filename: tempmailgrab-webhooks-api-openapi.yml
  format: yaml
  label: TempMailGrab API Webhooks API
  slug: tempmailgrab-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tempmailgrab/openapi/tempmailgrab-webhooks-api-openapi.yml
claim_count: 1
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
  - summary: Unlawful, fraudulent, harassing use
    text: Do not use the service for unlawful activity, fraud, or harassment.
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
name: TempMailGrab API
provenance_date: '2026-11-10'
provider_name: TempMailGrab API
provider_slug: tempmailgrab
slug: tempmailgrab-eligibility
source_date: '2026-11-10'
source_filename: tempmailgrab-eligibility.yml
source_heading: Eligibility
source_page: https://tempmailgrab.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: TempMailGrab API\naid: tempmailgrab\nurl: https://tempmailgrab.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful, fraudulent, harassing use\n  text: Do not use the service for unlawful activity, fraud, or harassment.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/tempmailgrab/eligibility/tempmailgrab-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from TempMailGrab API's own page on 2026-11-10.
synthetic: false
tags:
- Email
- temporary-email
- Disposable Email
- OTP
- Webhook
- QA
- Testing
- Playwright
- Cypress
- Developer Tools
- Email Testing
- CI
---
