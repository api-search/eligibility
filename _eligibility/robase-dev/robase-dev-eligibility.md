---
api_specs:
- filename: robase-dev-dashboard-api-openapi.yml
  format: yaml
  label: robase-dev Dashboard API
  slug: robase-dev-dashboard-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/robase-dev/openapi/robase-dev-dashboard-api-openapi.yml
- filename: robase-dev-otp-api-openapi.yml
  format: yaml
  label: robase-dev OTP API
  slug: robase-dev-otp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/robase-dev/openapi/robase-dev-otp-api-openapi.yml
- filename: robase-dev-sms-api-openapi.yml
  format: yaml
  label: robase-dev SMS API
  slug: robase-dev-sms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/robase-dev/openapi/robase-dev-sms-api-openapi.yml
- filename: robase-dev-system-api-openapi.yml
  format: yaml
  label: robase-dev System API
  slug: robase-dev-system-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/robase-dev/openapi/robase-dev-system-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Robase provides an API for sending SMS OTP messages and transactional SMS through multi-provider routing across Africa.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Non-compliant messaging
    text: You must obtain all necessary consents from recipients before sending messages, including opt-in consent where required by applicable law.
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
name: robase-dev
provenance_date: '2026-11-10'
provider_name: robase-dev
provider_slug: robase-dev
slug: robase-dev-eligibility
source_date: '2026-11-10'
source_filename: robase-dev-eligibility.yml
source_heading: Eligibility
source_page: https://robase.dev/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: robase-dev\naid: robase-dev\nurl: https://robase.dev/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Robase provides an API for sending SMS OTP messages and transactional SMS through multi-provider routing\n    across Africa.\nentity_types: []\nrestricted_uses:\n- summary: Non-compliant messaging\n  text: You must obtain all necessary consents from recipients before sending messages, including opt-in consent\n    where required by applicable law.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/robase-dev/eligibility/robase-dev-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from robase-dev's own page on 2026-11-10.
synthetic: false
tags:
- SMS
- OTP
- Africa
- Messaging
- Communications
---
