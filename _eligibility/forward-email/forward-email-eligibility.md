---
api_specs:
- filename: forward-email-account-api-openapi.yml
  format: yaml
  label: Forward Email Account API
  slug: forward-email-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/forward-email/openapi/forward-email-account-api-openapi.yml
- filename: forward-email-aliases-api-openapi.yml
  format: yaml
  label: Forward Email Aliases API
  slug: forward-email-aliases-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/forward-email/openapi/forward-email-aliases-api-openapi.yml
- filename: forward-email-calendar-events-api-openapi.yml
  format: yaml
  label: Forward Email Calendar Events API
  slug: forward-email-calendar-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/forward-email/openapi/forward-email-calendar-events-api-openapi.yml
- filename: forward-email-calendars-api-openapi.yml
  format: yaml
  label: Forward Email Calendars API
  slug: forward-email-calendars-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/forward-email/openapi/forward-email-calendars-api-openapi.yml
- filename: forward-email-contacts-api-openapi.yml
  format: yaml
  label: Forward Email Contacts API
  slug: forward-email-contacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/forward-email/openapi/forward-email-contacts-api-openapi.yml
- filename: forward-email-domains-api-openapi.yml
  format: yaml
  label: Forward Email Domains API
  slug: forward-email-domains-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/forward-email/openapi/forward-email-domains-api-openapi.yml
- filename: forward-email-emails-api-openapi.yml
  format: yaml
  label: Forward Email Emails API
  slug: forward-email-emails-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/forward-email/openapi/forward-email-emails-api-openapi.yml
- filename: forward-email-encrypt-api-openapi.yml
  format: yaml
  label: Forward Email Encrypt API
  slug: forward-email-encrypt-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/forward-email/openapi/forward-email-encrypt-api-openapi.yml
- filename: forward-email-folders-api-openapi.yml
  format: yaml
  label: Forward Email Folders API
  slug: forward-email-folders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/forward-email/openapi/forward-email-folders-api-openapi.yml
- filename: forward-email-invites-api-openapi.yml
  format: yaml
  label: Forward Email Invites API
  slug: forward-email-invites-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/forward-email/openapi/forward-email-invites-api-openapi.yml
- filename: forward-email-logs-api-openapi.yml
  format: yaml
  label: Forward Email Logs API
  slug: forward-email-logs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/forward-email/openapi/forward-email-logs-api-openapi.yml
- filename: forward-email-members-api-openapi.yml
  format: yaml
  label: Forward Email Members API
  slug: forward-email-members-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/forward-email/openapi/forward-email-members-api-openapi.yml
- filename: forward-email-messages-api-openapi.yml
  format: yaml
  label: Forward Email Messages API
  slug: forward-email-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/forward-email/openapi/forward-email-messages-api-openapi.yml
- filename: forward-email-push-tokens-api-openapi.yml
  format: yaml
  label: Forward Email Push Tokens API
  slug: forward-email-push-tokens-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/forward-email/openapi/forward-email-push-tokens-api-openapi.yml
- filename: forward-email-sieve-scripts-api-openapi.yml
  format: yaml
  label: Forward Email Sieve Scripts API
  slug: forward-email-sieve-scripts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/forward-email/openapi/forward-email-sieve-scripts-api-openapi.yml
- filename: forward-email-websockets-api-openapi.yml
  format: yaml
  label: Forward Email WebSockets API
  slug: forward-email-websockets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/forward-email/openapi/forward-email-websockets-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You must be at least eighteen (18) years of age, or between thirteen (13) and seventeen (17) years of age and using the Service with parental or legal guardian consent and supervision.
    value: '13'
  restricted_uses:
  - summary: Email marketing must be opt-in with List-Unsubscribe
    text: If you are sending email marketing material, then you must include a List-Unsubscribe header and your subscribers must be opt-in.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: The first-time your domain name attempts to send a newsletter, an admin will review and approve your domain for sending newsletters (usually within 2-4 hours, but sometimes it may take longer).
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Forward Email
provenance_date: '2026-11-09'
provider_name: Forward Email
provider_slug: forward-email
slug: forward-email-eligibility
source_date: '2026-11-09'
source_filename: forward-email-eligibility.yml
source_heading: Eligibility
source_page: https://forwardemail.net/en/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Forward Email\naid: forward-email\nurl: https://forwardemail.net/en/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Email marketing must be opt-in with List-Unsubscribe\n  text: If you are sending email marketing material, then you must include a List-Unsubscribe header and your subscribers\n    must be opt-in.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: The first-time your domain name attempts to send a newsletter, an admin will review and approve your domain\n    for sending newsletters\
  \ (usually within 2-4 hours, but sometimes it may take longer).\nminimum_age:\n  value: '13'\n  text: You must be at least eighteen (18) years of age, or between thirteen (13) and seventeen (17) years of age\n    and using the Service with parental or legal guardian consent and supervision.\n"
source_yaml_url: https://artifacts.apis.io/forward-email/eligibility/forward-email-eligibility.yml
stated_fields:
- restricted_uses
- verification
- minimum_age
summary_line: 3 quoted statements, read from Forward Email's own page on 2026-11-09.
synthetic: false
tags:
- Email Forwarding
- Email Hosting
- Open Source
- Secure Email
---
