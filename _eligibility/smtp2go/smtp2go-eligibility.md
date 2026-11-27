---
api_specs:
- filename: smtp2go-activity-api-openapi.yml
  format: yaml
  label: SMTP2GO Activity API
  slug: smtp2go-activity-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smtp2go/openapi/smtp2go-activity-api-openapi.yml
- filename: smtp2go-api-keys-api-openapi.yml
  format: yaml
  label: SMTP2GO API Keys API
  slug: smtp2go-api-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smtp2go/openapi/smtp2go-api-keys-api-openapi.yml
- filename: smtp2go-sms-api-openapi.yml
  format: yaml
  label: SMTP2GO SMS API
  slug: smtp2go-sms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smtp2go/openapi/smtp2go-sms-api-openapi.yml
- filename: smtp2go-smtp-users-api-openapi.yml
  format: yaml
  label: SMTP2GO SMTP Users API
  slug: smtp2go-smtp-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smtp2go/openapi/smtp2go-smtp-users-api-openapi.yml
- filename: smtp2go-subaccounts-api-openapi.yml
  format: yaml
  label: SMTP2GO Subaccounts API
  slug: smtp2go-subaccounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smtp2go/openapi/smtp2go-subaccounts-api-openapi.yml
- filename: smtp2go-suppressions-api-openapi.yml
  format: yaml
  label: SMTP2GO Suppressions API
  slug: smtp2go-suppressions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smtp2go/openapi/smtp2go-suppressions-api-openapi.yml
- filename: smtp2go-templates-api-openapi.yml
  format: yaml
  label: SMTP2GO Templates API
  slug: smtp2go-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smtp2go/openapi/smtp2go-templates-api-openapi.yml
- filename: smtp2go-webhooks-api-openapi.yml
  format: yaml
  label: SMTP2GO Webhooks API
  slug: smtp2go-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smtp2go/openapi/smtp2go-webhooks-api-openapi.yml
- filename: smtp2go-allowed-recipients-api-openapi.yml
  format: yaml
  label: SMTP2GO ALLOWED RECIPIENTS API
  slug: smtp2go-allowed-recipients-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smtp2go/openapi/smtp2go-allowed-recipients-api-openapi.yml
- filename: smtp2go-allowed-senders-api-openapi.yml
  format: yaml
  label: SMTP2GO ALLOWED SENDERS API
  slug: smtp2go-allowed-senders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smtp2go/openapi/smtp2go-allowed-senders-api-openapi.yml
- filename: smtp2go-dedicated-ips-api-openapi.yml
  format: yaml
  label: SMTP2GO DEDICATED IPS API
  slug: smtp2go-dedicated-ips-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smtp2go/openapi/smtp2go-dedicated-ips-api-openapi.yml
- filename: smtp2go-email-archive-api-openapi.yml
  format: yaml
  label: SMTP2GO EMAIL ARCHIVE API
  slug: smtp2go-email-archive-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smtp2go/openapi/smtp2go-email-archive-api-openapi.yml
- filename: smtp2go-emails-api-openapi.yml
  format: yaml
  label: SMTP2GO EMAILS API
  slug: smtp2go-emails-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smtp2go/openapi/smtp2go-emails-api-openapi.yml
- filename: smtp2go-ip-auth-api-openapi.yml
  format: yaml
  label: SMTP2GO IP AUTH API
  slug: smtp2go-ip-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smtp2go/openapi/smtp2go-ip-auth-api-openapi.yml
- filename: smtp2go-sender-domains-api-openapi.yml
  format: yaml
  label: SMTP2GO SENDER DOMAINS API
  slug: smtp2go-sender-domains-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smtp2go/openapi/smtp2go-sender-domains-api-openapi.yml
- filename: smtp2go-single-sender-emails-api-openapi.yml
  format: yaml
  label: SMTP2GO SINGLE SENDER EMAILS API
  slug: smtp2go-single-sender-emails-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smtp2go/openapi/smtp2go-single-sender-emails-api-openapi.yml
- filename: smtp2go-statistics-api-openapi.yml
  format: yaml
  label: SMTP2GO STATISTICS API
  slug: smtp2go-statistics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smtp2go/openapi/smtp2go-statistics-api-openapi.yml
- filename: smtp2go-ip-allowlist-api-openapi.yml
  format: yaml
  label: SMTP2GO IP Allowlist API
  slug: smtp2go-ip-allowlist-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smtp2go/openapi/smtp2go-ip-allowlist-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Businesses must not create more than 10 free plan accounts.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Restricted industry content
    text: Pornographic or adult content
  - summary: Email-to-SMS limit
    text: Emails sent to external email-to-SMS services exceeding 100 messages per month, and none for marketing purposes
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
name: SMTP2GO
provenance_date: '2026-11-10'
provider_name: SMTP2GO
provider_slug: smtp2go
slug: smtp2go-eligibility
source_date: '2026-11-10'
source_filename: smtp2go-eligibility.yml
source_heading: Eligibility
source_page: https://www.smtp2go.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: SMTP2GO\naid: smtp2go\nurl: https://www.smtp2go.com/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Businesses must not create more than 10 free plan accounts.\nrestricted_uses:\n- summary: Restricted industry content\n  text: Pornographic or adult content\n- summary: Email-to-SMS limit\n  text: Emails sent to external email-to-SMS services exceeding 100 messages per month, and none for marketing purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/smtp2go/eligibility/smtp2go-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from SMTP2GO's own page on 2026-11-10.
synthetic: false
tags:
- Email
- Email Delivery
- Transactional Email
- SMTP
- SMS
- Email API
- Deliverability
- Webhook
- Messaging
- Communications
- MCP
- Agent Skills
---
