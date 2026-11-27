---
api_specs:
- filename: persona-accounts-api-openapi.yml
  format: yaml
  label: Persona Accounts API
  slug: persona-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/persona/openapi/persona-accounts-api-openapi.yml
- filename: persona-inquiries-api-openapi.yml
  format: yaml
  label: Persona Inquiries API
  slug: persona-inquiries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/persona/openapi/persona-inquiries-api-openapi.yml
- filename: persona-lists-api-openapi.yml
  format: yaml
  label: Persona Lists API
  slug: persona-lists-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/persona/openapi/persona-lists-api-openapi.yml
- filename: persona-reports-api-openapi.yml
  format: yaml
  label: Persona Reports API
  slug: persona-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/persona/openapi/persona-reports-api-openapi.yml
- filename: persona-transactions-api-openapi.yml
  format: yaml
  label: Persona Transactions API
  slug: persona-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/persona/openapi/persona-transactions-api-openapi.yml
- filename: persona-verifications-api-openapi.yml
  format: yaml
  label: Persona Verifications API
  slug: persona-verifications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/persona/openapi/persona-verifications-api-openapi.yml
- filename: persona-webhooks-api-openapi.yml
  format: yaml
  label: Persona Webhooks API
  slug: persona-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/persona/openapi/persona-webhooks-api-openapi.yml
- filename: persona-cases-api-openapi.yml
  format: yaml
  label: Persona Cases API
  slug: persona-cases-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/persona/openapi/persona-cases-api-openapi.yml
- filename: persona-devices-api-openapi.yml
  format: yaml
  label: Persona Devices API
  slug: persona-devices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/persona/openapi/persona-devices-api-openapi.yml
- filename: persona-documents-api-openapi.yml
  format: yaml
  label: Persona Documents API
  slug: persona-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/persona/openapi/persona-documents-api-openapi.yml
- filename: persona-events-api-openapi.yml
  format: yaml
  label: Persona Events API
  slug: persona-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/persona/openapi/persona-events-api-openapi.yml
- filename: persona-importers-api-openapi.yml
  format: yaml
  label: Persona Importers API
  slug: persona-importers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/persona/openapi/persona-importers-api-openapi.yml
- filename: persona-inquiry-sessions-api-openapi.yml
  format: yaml
  label: Persona Inquiry Sessions API
  slug: persona-inquiry-sessions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/persona/openapi/persona-inquiry-sessions-api-openapi.yml
- filename: persona-workflows-api-openapi.yml
  format: yaml
  label: Persona Workflows API
  slug: persona-workflows-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/persona/openapi/persona-workflows-api-openapi.yml
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
  - summary: Lawful, responsible use only
    text: You must only use the Site and anything available from the Site for lawful purposes (complying with all applicable laws and regulations), in a responsible manner
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
name: Persona
provenance_date: '2026-11-10'
provider_name: Persona
provider_slug: persona
slug: persona-eligibility
source_date: '2026-11-10'
source_filename: persona-eligibility.yml
source_heading: Eligibility
source_page: https://withpersona.com/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Persona\naid: persona\nurl: https://withpersona.com/legal/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Lawful, responsible use only\n  text: You must only use the Site and anything available from the Site for lawful purposes (complying with all\n    applicable laws and regulations), in a responsible manner\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/persona/eligibility/persona-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Persona's own page on 2026-11-10.
synthetic: false
tags:
- Fraud Prevention
- Identity Verification
- KYC
---
