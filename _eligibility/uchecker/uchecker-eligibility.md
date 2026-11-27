---
api_specs:
- filename: uchecker-default-api-openapi.yml
  format: yaml
  label: uChecker Аутентификация API
  slug: uchecker-default-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/uchecker/openapi/uchecker-default-api-openapi.yml
- filename: uchecker-email-api-openapi.yml
  format: yaml
  label: uChecker Валидация Email API
  slug: uchecker-email-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/uchecker/openapi/uchecker-email-api-openapi.yml
- filename: uchecker-esp-api-openapi.yml
  format: yaml
  label: uChecker ESP Провайдеры API
  slug: uchecker-esp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/uchecker/openapi/uchecker-esp-api-openapi.yml
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
  - summary: No spam or unlawful mailings
    text: The user agrees not to use the Service for sending spam, unlawful mailings, or any other actions contrary to applicable law.
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
name: uChecker
provenance_date: '2026-11-10'
provider_name: uChecker
provider_slug: uchecker
slug: uchecker-eligibility
source_date: '2026-11-10'
source_filename: uchecker-eligibility.yml
source_heading: Eligibility
source_page: https://uchecker.net/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: uChecker\naid: uchecker\nurl: https://uchecker.net/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: No spam or unlawful mailings\n  text: The user agrees not to use the Service for sending spam, unlawful mailings, or any other actions contrary\n    to applicable law.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/uchecker/eligibility/uchecker-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from uChecker's own page on 2026-11-10.
synthetic: false
tags:
- Email Verification
- Email
- SMTP
- DNS
- Deliverability
- MX
- SPF
- DKIM
- DMARC
- MCP
- Agent-Native
- Data Quality
---
