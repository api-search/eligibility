---
api_specs:
- filename: verifly-email-account-api-openapi.yml
  format: yaml
  label: verifly-email Account API
  slug: verifly-email-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/verifly-email/openapi/verifly-email-account-api-openapi.yml
- filename: verifly-email-billing-api-openapi.yml
  format: yaml
  label: verifly-email Billing API
  slug: verifly-email-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/verifly-email/openapi/verifly-email-billing-api-openapi.yml
- filename: verifly-email-clean-api-openapi.yml
  format: yaml
  label: verifly-email Clean API
  slug: verifly-email-clean-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/verifly-email/openapi/verifly-email-clean-api-openapi.yml
- filename: verifly-email-extract-api-openapi.yml
  format: yaml
  label: verifly-email Extract API
  slug: verifly-email-extract-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/verifly-email/openapi/verifly-email-extract-api-openapi.yml
- filename: verifly-email-files-api-openapi.yml
  format: yaml
  label: verifly-email Files API
  slug: verifly-email-files-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/verifly-email/openapi/verifly-email-files-api-openapi.yml
- filename: verifly-email-jobs-api-openapi.yml
  format: yaml
  label: verifly-email Jobs API
  slug: verifly-email-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/verifly-email/openapi/verifly-email-jobs-api-openapi.yml
- filename: verifly-email-list-cleaning-api-openapi.yml
  format: yaml
  label: verifly-email List Cleaning API
  slug: verifly-email-list-cleaning-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/verifly-email/openapi/verifly-email-list-cleaning-api-openapi.yml
- filename: verifly-email-onboarding-api-openapi.yml
  format: yaml
  label: verifly-email Onboarding API
  slug: verifly-email-onboarding-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/verifly-email/openapi/verifly-email-onboarding-api-openapi.yml
- filename: verifly-email-tools-api-openapi.yml
  format: yaml
  label: verifly-email Tools API
  slug: verifly-email-tools-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/verifly-email/openapi/verifly-email-tools-api-openapi.yml
- filename: verifly-email-verification-api-openapi.yml
  format: yaml
  label: verifly-email Verification API
  slug: verifly-email-verification-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/verifly-email/openapi/verifly-email-verification-api-openapi.yml
- filename: verifly-email-verify-api-openapi.yml
  format: yaml
  label: verifly-email Verify API
  slug: verifly-email-verify-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/verifly-email/openapi/verifly-email-verify-api-openapi.yml
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
  - summary: Spamming or unsolicited bulk email
    text: Verify email addresses for spamming or unsolicited bulk email
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: To use certain features, you must create an account.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: verifly-email
provenance_date: '2026-11-10'
provider_name: verifly-email
provider_slug: verifly-email
slug: verifly-email-eligibility
source_date: '2026-11-10'
source_filename: verifly-email-eligibility.yml
source_heading: Eligibility
source_page: https://verifly.email/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: verifly-email\naid: verifly-email\nurl: https://verifly.email/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Spamming or unsolicited bulk email\n  text: Verify email addresses for spamming or unsolicited bulk email\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: To use certain features, you must create an account.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/verifly-email/eligibility/verifly-email-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from verifly-email's own page on 2026-11-10.
synthetic: false
tags:
- Email Verification
- MCP
- Developer Tools
- Verification
- Company
---
