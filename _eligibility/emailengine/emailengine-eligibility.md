---
api_specs:
- filename: emailengine-account-api-openapi.yml
  format: yaml
  label: EmailEngine Account API
  slug: emailengine-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/emailengine/openapi/emailengine-account-api-openapi.yml
- filename: emailengine-accounts-api-openapi.yml
  format: yaml
  label: EmailEngine Accounts API
  slug: emailengine-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/emailengine/openapi/emailengine-accounts-api-openapi.yml
- filename: emailengine-autoconfig-api-openapi.yml
  format: yaml
  label: EmailEngine Autoconfig API
  slug: emailengine-autoconfig-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/emailengine/openapi/emailengine-autoconfig-api-openapi.yml
- filename: emailengine-deliverytest-api-openapi.yml
  format: yaml
  label: EmailEngine Deliverytest API
  slug: emailengine-deliverytest-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/emailengine/openapi/emailengine-deliverytest-api-openapi.yml
- filename: emailengine-gateways-api-openapi.yml
  format: yaml
  label: EmailEngine Gateways API
  slug: emailengine-gateways-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/emailengine/openapi/emailengine-gateways-api-openapi.yml
- filename: emailengine-license-api-openapi.yml
  format: yaml
  label: EmailEngine License API
  slug: emailengine-license-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/emailengine/openapi/emailengine-license-api-openapi.yml
- filename: emailengine-logs-api-openapi.yml
  format: yaml
  label: EmailEngine Logs API
  slug: emailengine-logs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/emailengine/openapi/emailengine-logs-api-openapi.yml
- filename: emailengine-outbox-api-openapi.yml
  format: yaml
  label: EmailEngine Outbox API
  slug: emailengine-outbox-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/emailengine/openapi/emailengine-outbox-api-openapi.yml
- filename: emailengine-stats-api-openapi.yml
  format: yaml
  label: EmailEngine Stats API
  slug: emailengine-stats-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/emailengine/openapi/emailengine-stats-api-openapi.yml
- filename: emailengine-templates-api-openapi.yml
  format: yaml
  label: EmailEngine Templates API
  slug: emailengine-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/emailengine/openapi/emailengine-templates-api-openapi.yml
- filename: emailengine-tokens-api-openapi.yml
  format: yaml
  label: EmailEngine Tokens API
  slug: emailengine-tokens-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/emailengine/openapi/emailengine-tokens-api-openapi.yml
- filename: emailengine-webhookroutes-api-openapi.yml
  format: yaml
  label: EmailEngine Webhookroutes API
  slug: emailengine-webhookroutes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/emailengine/openapi/emailengine-webhookroutes-api-openapi.yml
- filename: emailengine-oauth2-api-openapi.yml
  format: yaml
  label: EmailEngine Oauth2 API
  slug: emailengine-oauth2-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/emailengine/openapi/emailengine-oauth2-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: Service is intended only for access and use by individuals at least eighteen (18) years old.
    value: '18'
  restricted_uses:
  - summary: Spam and unsolicited advertising
    text: To transmit, or procure the sending of, any advertising or promotional material, including any “junk mail”, “chain letter,” “spam,” or any other similar solicitation.
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
name: EmailEngine
provenance_date: '2026-11-09'
provider_name: EmailEngine
provider_slug: emailengine
slug: emailengine-eligibility
source_date: '2026-11-09'
source_filename: emailengine-eligibility.yml
source_heading: Eligibility
source_page: https://postalsys.com/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: EmailEngine\naid: emailengine\nurl: https://postalsys.com/tos\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Spam and unsolicited advertising\n  text: To transmit, or procure the sending of, any advertising or promotional material, including any “junk mail”,\n    “chain letter,” “spam,” or any other similar solicitation.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Service is intended only for access and use by individuals at least eighteen (18) years old.\n"
source_yaml_url: https://artifacts.apis.io/emailengine/eligibility/emailengine-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from EmailEngine's own page on 2026-11-09.
synthetic: false
tags:
- Email
- Email API
- IMAP
- SMTP
- Webhook
---
