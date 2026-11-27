---
api_specs:
- filename: mailosaur-analysis-api-openapi.yml
  format: yaml
  label: Mailosaur Analysis API
  slug: mailosaur-analysis-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mailosaur/openapi/mailosaur-analysis-api-openapi.yml
- filename: mailosaur-devices-api-openapi.yml
  format: yaml
  label: Mailosaur Devices API
  slug: mailosaur-devices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mailosaur/openapi/mailosaur-devices-api-openapi.yml
- filename: mailosaur-files-api-openapi.yml
  format: yaml
  label: Mailosaur Files API
  slug: mailosaur-files-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mailosaur/openapi/mailosaur-files-api-openapi.yml
- filename: mailosaur-messages-api-openapi.yml
  format: yaml
  label: Mailosaur Messages API
  slug: mailosaur-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mailosaur/openapi/mailosaur-messages-api-openapi.yml
- filename: mailosaur-previews-api-openapi.yml
  format: yaml
  label: Mailosaur Previews API
  slug: mailosaur-previews-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mailosaur/openapi/mailosaur-previews-api-openapi.yml
- filename: mailosaur-servers-api-openapi.yml
  format: yaml
  label: Mailosaur Servers API
  slug: mailosaur-servers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mailosaur/openapi/mailosaur-servers-api-openapi.yml
- filename: mailosaur-usage-api-openapi.yml
  format: yaml
  label: Mailosaur Usage API
  slug: mailosaur-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mailosaur/openapi/mailosaur-usage-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: The Customer warrants that all Users are over the age of 16.
    value: '16'
  restricted_uses:
  - summary: Unlawful or harmful material
    text: The Customer shall not access, store, distribute or transmit any viruses, or any material (including Customer Data)
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
name: Mailosaur
provenance_date: '2026-11-10'
provider_name: Mailosaur
provider_slug: mailosaur
slug: mailosaur-eligibility
source_date: '2026-11-10'
source_filename: mailosaur-eligibility.yml
source_heading: Eligibility
source_page: https://mailosaur.com/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Mailosaur\naid: mailosaur\nurl: https://mailosaur.com/legal/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful or harmful material\n  text: The Customer shall not access, store, distribute or transmit any viruses, or any material (including Customer\n    Data)\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: The Customer warrants that all Users are over the age of 16.\n"
source_yaml_url: https://artifacts.apis.io/mailosaur/eligibility/mailosaur-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Mailosaur's own page on 2026-11-10.
synthetic: false
tags:
- Email Testing
- SMS Testing
- Developer Tools
- QA Automation
- CI/CD
- SMTP
- TOTP
- Deliverability
---
