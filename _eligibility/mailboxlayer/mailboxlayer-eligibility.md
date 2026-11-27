---
api_specs:
- filename: mailboxlayer-bulk-check-api-openapi.yml
  format: yaml
  label: Mailboxlayer Bulk Check API
  slug: mailboxlayer-bulk-check-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mailboxlayer/openapi/mailboxlayer-bulk-check-api-openapi.yml
- filename: mailboxlayer-check-api-openapi.yml
  format: yaml
  label: Mailboxlayer Check API
  slug: mailboxlayer-check-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mailboxlayer/openapi/mailboxlayer-check-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are a consumer, please note that these Terms & Conditions, its subject matter and its formation, are governed by Austrian law.
    type: individual
  - text: If you are a business, these Terms & Conditions, its subject matter and its formation (and any non-contractual disputes or claims) are governed by Austrian law.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Use violating law
    text: use mailboxlayer API Data & Services or the mailboxlayer API in any manner or for any purpose that violates any law, regulation or right of any person.
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
name: Mailboxlayer
provenance_date: '2026-11-10'
provider_name: Mailboxlayer
provider_slug: mailboxlayer
slug: mailboxlayer-eligibility
source_date: '2026-11-10'
source_filename: mailboxlayer-eligibility.yml
source_heading: Eligibility
source_page: https://mailboxlayer.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Mailboxlayer\naid: mailboxlayer\nurl: https://mailboxlayer.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: If you are a consumer, please note that these Terms & Conditions, its subject matter and its formation,\n    are governed by Austrian law.\n- type: business\n  text: If you are a business, these Terms & Conditions, its subject matter and its formation (and any non-contractual\n    disputes or claims) are governed by Austrian law.\nrestricted_uses:\n- summary: Use violating law\n  text: use mailboxlayer API Data & Services\
  \ or the mailboxlayer API in any manner or for any purpose that violates\n    any law, regulation or right of any person.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/mailboxlayer/eligibility/mailboxlayer-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Mailboxlayer's own page on 2026-11-10.
synthetic: false
tags:
- Email
- Email Verification
- SMTP
- MX Records
- Catch-All Detection
- Disposable Email
- Free Email Provider
- Role Address
- Quality Score
- APILayer
- Public APIs
- Data Quality
- Fraud Prevention
- Deliverability
- Communications
- Developer Tools
- Security
---
