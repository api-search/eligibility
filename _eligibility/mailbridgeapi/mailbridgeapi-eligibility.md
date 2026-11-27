---
api_specs:
- filename: mailbridgeapi-activity-api-openapi.yml
  format: yaml
  label: MailBridgeAPI Activity API
  slug: mailbridgeapi-activity-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mailbridgeapi/openapi/mailbridgeapi-activity-api-openapi.yml
- filename: mailbridgeapi-compliance-api-openapi.yml
  format: yaml
  label: MailBridgeAPI Compliance API
  slug: mailbridgeapi-compliance-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mailbridgeapi/openapi/mailbridgeapi-compliance-api-openapi.yml
- filename: mailbridgeapi-mailbox-api-openapi.yml
  format: yaml
  label: MailBridgeAPI Mailbox API
  slug: mailbridgeapi-mailbox-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mailbridgeapi/openapi/mailbridgeapi-mailbox-api-openapi.yml
- filename: mailbridgeapi-receiving-api-openapi.yml
  format: yaml
  label: MailBridgeAPI Receiving API
  slug: mailbridgeapi-receiving-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mailbridgeapi/openapi/mailbridgeapi-receiving-api-openapi.yml
- filename: mailbridgeapi-sending-api-openapi.yml
  format: yaml
  label: MailBridgeAPI Sending API
  slug: mailbridgeapi-sending-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mailbridgeapi/openapi/mailbridgeapi-sending-api-openapi.yml
- filename: mailbridgeapi-service-api-openapi.yml
  format: yaml
  label: MailBridgeAPI Service API
  slug: mailbridgeapi-service-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mailbridgeapi/openapi/mailbridgeapi-service-api-openapi.yml
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
  - summary: Illegal or unauthorized purposes
    text: Users must not use the service for any illegal or unauthorized purposes.
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
name: MailBridgeAPI
provenance_date: '2026-11-10'
provider_name: MailBridgeAPI
provider_slug: mailbridgeapi
slug: mailbridgeapi-eligibility
source_date: '2026-11-10'
source_filename: mailbridgeapi-eligibility.yml
source_heading: Eligibility
source_page: https://mailbridgeapi.com/terms-and-conditions-of-sale/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: MailBridgeAPI\naid: mailbridgeapi\nurl: https://mailbridgeapi.com/terms-and-conditions-of-sale/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Illegal or unauthorized purposes\n  text: Users must not use the service for any illegal or unauthorized purposes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/mailbridgeapi/eligibility/mailbridgeapi-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from MailBridgeAPI's own page on 2026-11-10.
synthetic: false
tags:
- Email API
- SMTP
- IMAP
- mailbox integration
- Developer Tools
- mailbox monitoring
---
