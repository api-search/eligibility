---
api_specs:
- filename: inflectionio-contact-activity-api-openapi.yml
  format: yaml
  label: Inflection.io Contact Activity API
  slug: inflectionio-contact-activity-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/inflectionio/openapi/inflectionio-contact-activity-api-openapi.yml
- filename: inflectionio-contacts-api-openapi.yml
  format: yaml
  label: Inflection.io Contacts API
  slug: inflectionio-contacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/inflectionio/openapi/inflectionio-contacts-api-openapi.yml
- filename: inflectionio-emails-api-openapi.yml
  format: yaml
  label: Inflection.io Emails API
  slug: inflectionio-emails-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/inflectionio/openapi/inflectionio-emails-api-openapi.yml
- filename: inflectionio-email-versions-api-openapi.yml
  format: yaml
  label: Inflection.io Email Versions API
  slug: inflectionio-email-versions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/inflectionio/openapi/inflectionio-email-versions-api-openapi.yml
- filename: inflectionio-journeys-api-openapi.yml
  format: yaml
  label: Inflection.io Journeys API
  slug: inflectionio-journeys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/inflectionio/openapi/inflectionio-journeys-api-openapi.yml
- filename: inflectionio-lists-api-openapi.yml
  format: yaml
  label: Inflection.io Lists API
  slug: inflectionio-lists-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/inflectionio/openapi/inflectionio-lists-api-openapi.yml
- filename: inflectionio-organizations-api-openapi.yml
  format: yaml
  label: Inflection.io Organizations API
  slug: inflectionio-organizations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/inflectionio/openapi/inflectionio-organizations-api-openapi.yml
- filename: inflectionio-product-users-api-openapi.yml
  format: yaml
  label: Inflection.io Product Users API
  slug: inflectionio-product-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/inflectionio/openapi/inflectionio-product-users-api-openapi.yml
- filename: inflectionio-stats-api-openapi.yml
  format: yaml
  label: Inflection.io Stats API
  slug: inflectionio-stats-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/inflectionio/openapi/inflectionio-stats-api-openapi.yml
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
  - summary: Spam and unconsented email
    text: Customer may not send emails to persons who have not granted verifiable consent to the receipt of such emails according to Applicable Law.
  - summary: Sensitive information
    text: Customer is strictly prohibited from transmitting or providing to Provider any sensitive information as that term may be used in Applicable Laws
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
name: Inflection.io
provenance_date: '2026-11-09'
provider_name: Inflection.io
provider_slug: inflectionio
slug: inflectionio-eligibility
source_date: '2026-11-09'
source_filename: inflectionio-eligibility.yml
source_heading: Eligibility
source_page: https://www.inflection.io/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Inflection.io\naid: inflectionio\nurl: https://www.inflection.io/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Spam and unconsented email\n  text: Customer may not send emails to persons who have not granted verifiable consent to the receipt of such emails\n    according to Applicable Law.\n- summary: Sensitive information\n  text: Customer is strictly prohibited from transmitting or providing to Provider any sensitive information as\n    that term may be used in Applicable Laws\nverification:\n  kyc: null\n  kyb:\
  \ null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/inflectionio/eligibility/inflectionio-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 2 quoted statements, read from Inflection.io's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Software-as-a-Service
- Marketing
- Marketing Automation
- Email Marketing
- Customer Data
- B2B
- Contacts
- MCP
- Agents
- Artificial Intelligence
- Customer Journey
- Webhook
- A2A
---
