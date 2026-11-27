---
api_specs:
- filename: mailsenpai-account-api-openapi.yml
  format: yaml
  label: SMTP Senpai (MailSenpai) Account API
  slug: mailsenpai-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mailsenpai/openapi/mailsenpai-account-api-openapi.yml
- filename: mailsenpai-log-api-openapi.yml
  format: yaml
  label: SMTP Senpai (MailSenpai) Log API
  slug: mailsenpai-log-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mailsenpai/openapi/mailsenpai-log-api-openapi.yml
- filename: mailsenpai-sending-api-openapi.yml
  format: yaml
  label: SMTP Senpai (MailSenpai) Sending API
  slug: mailsenpai-sending-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mailsenpai/openapi/mailsenpai-sending-api-openapi.yml
- filename: mailsenpai-suppression-api-openapi.yml
  format: yaml
  label: SMTP Senpai (MailSenpai) Suppression API
  slug: mailsenpai-suppression-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mailsenpai/openapi/mailsenpai-suppression-api-openapi.yml
- filename: mailsenpai-webhooks-api-openapi.yml
  format: yaml
  label: SMTP Senpai (MailSenpai) Webhooks API
  slug: mailsenpai-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mailsenpai/openapi/mailsenpai-webhooks-api-openapi.yml
- filename: mailsenpai-website-forms-api-openapi.yml
  format: yaml
  label: SMTP Senpai (MailSenpai) Website forms API
  slug: mailsenpai-website-forms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mailsenpai/openapi/mailsenpai-website-forms-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: if acting on behalf of an entity, have the necessary authority to sign this Agreement
    type: business
  minimum_age:
    text: They are of legal age
    value: legal age
  restricted_uses:
  - summary: Prohibited content
    text: Sending messages that are immoral, against public order, or intended to disturb public or private peace, offend, or directly or indirectly harm third parties;
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
name: SMTP Senpai (MailSenpai)
provenance_date: '2026-11-10'
provider_name: SMTP Senpai (MailSenpai)
provider_slug: mailsenpai
slug: mailsenpai-eligibility
source_date: '2026-11-10'
source_filename: mailsenpai-eligibility.yml
source_heading: Eligibility
source_page: https://en.mailsenpai.com/tc/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: SMTP Senpai (MailSenpai)\naid: mailsenpai\nurl: https://en.mailsenpai.com/tc/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: if acting on behalf of an entity, have the necessary authority to sign this Agreement\nrestricted_uses:\n- summary: Prohibited content\n  text: Sending messages that are immoral, against public order, or intended to disturb public or private peace,\n    offend, or directly or indirectly harm third parties;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: legal age\n  text: They are of legal age\n"
source_yaml_url: https://artifacts.apis.io/mailsenpai/eligibility/mailsenpai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from SMTP Senpai (MailSenpai)'s own page on 2026-11-10.
synthetic: false
tags:
- Email Marketing
- B2B outreach
- SMTP relay
- Artificial Intelligence
- Newsletter platform
---
