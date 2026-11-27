---
api_specs:
- filename: mailjet-campaigns-api-openapi.yml
  format: yaml
  label: Mailjet Campaigns API
  slug: mailjet-campaigns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mailjet/openapi/mailjet-campaigns-api-openapi.yml
- filename: mailjet-contact-lists-api-openapi.yml
  format: yaml
  label: Mailjet Contact Lists API
  slug: mailjet-contact-lists-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mailjet/openapi/mailjet-contact-lists-api-openapi.yml
- filename: mailjet-contacts-api-openapi.yml
  format: yaml
  label: Mailjet Contacts API
  slug: mailjet-contacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mailjet/openapi/mailjet-contacts-api-openapi.yml
- filename: mailjet-event-api-openapi.yml
  format: yaml
  label: Mailjet Event API
  slug: mailjet-event-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mailjet/openapi/mailjet-event-api-openapi.yml
- filename: mailjet-send-api-openapi.yml
  format: yaml
  label: Mailjet Send API
  slug: mailjet-send-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mailjet/openapi/mailjet-send-api-openapi.yml
- filename: mailjet-senders-api-openapi.yml
  format: yaml
  label: Mailjet Senders API
  slug: mailjet-senders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mailjet/openapi/mailjet-senders-api-openapi.yml
- filename: mailjet-statistics-api-openapi.yml
  format: yaml
  label: Mailjet Statistics API
  slug: mailjet-statistics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mailjet/openapi/mailjet-statistics-api-openapi.yml
- filename: mailjet-templates-api-openapi.yml
  format: yaml
  label: Mailjet Templates API
  slug: mailjet-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mailjet/openapi/mailjet-templates-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: The Services are exclusively reserved for a professional use and are not available to minors under the age of 18.
    value: '18'
  restricted_uses:
  - summary: Sensitive personal data
    text: Customer agrees not to provide Sinch Email or use the Services in connection with any sensitive personal data or protected health information
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
name: Mailjet
provenance_date: '2026-11-10'
provider_name: Mailjet
provider_slug: mailjet
slug: mailjet-eligibility
source_date: '2026-11-10'
source_filename: mailjet-eligibility.yml
source_heading: Eligibility
source_page: https://www.mailjet.com/legal/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Mailjet\naid: mailjet\nurl: https://www.mailjet.com/legal/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Sensitive personal data\n  text: Customer agrees not to provide Sinch Email or use the Services in connection with any sensitive personal\n    data or protected health information\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Services are exclusively reserved for a professional use and are not available to minors under the age\n    of 18.\n"
source_yaml_url: https://artifacts.apis.io/mailjet/eligibility/mailjet-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Mailjet's own page on 2026-11-10.
synthetic: false
tags:
- Email
- Email Delivery
- Marketing Email
- SMTP
- Transactional Email
---
