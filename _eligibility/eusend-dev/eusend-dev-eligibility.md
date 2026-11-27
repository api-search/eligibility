---
api_specs:
- filename: eusend-dev-api-keys-api-openapi.yml
  format: yaml
  label: eusend-dev API keys API
  slug: eusend-dev-api-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eusend-dev/openapi/eusend-dev-api-keys-api-openapi.yml
- filename: eusend-dev-audiences-api-openapi.yml
  format: yaml
  label: eusend-dev Audiences API
  slug: eusend-dev-audiences-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eusend-dev/openapi/eusend-dev-audiences-api-openapi.yml
- filename: eusend-dev-broadcasts-api-openapi.yml
  format: yaml
  label: eusend-dev Broadcasts API
  slug: eusend-dev-broadcasts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eusend-dev/openapi/eusend-dev-broadcasts-api-openapi.yml
- filename: eusend-dev-contact-properties-api-openapi.yml
  format: yaml
  label: eusend-dev Contact properties API
  slug: eusend-dev-contact-properties-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eusend-dev/openapi/eusend-dev-contact-properties-api-openapi.yml
- filename: eusend-dev-contacts-api-openapi.yml
  format: yaml
  label: eusend-dev Contacts API
  slug: eusend-dev-contacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eusend-dev/openapi/eusend-dev-contacts-api-openapi.yml
- filename: eusend-dev-domains-api-openapi.yml
  format: yaml
  label: eusend-dev Domains API
  slug: eusend-dev-domains-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eusend-dev/openapi/eusend-dev-domains-api-openapi.yml
- filename: eusend-dev-emails-api-openapi.yml
  format: yaml
  label: eusend-dev Emails API
  slug: eusend-dev-emails-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eusend-dev/openapi/eusend-dev-emails-api-openapi.yml
- filename: eusend-dev-suppressions-api-openapi.yml
  format: yaml
  label: eusend-dev Suppressions API
  slug: eusend-dev-suppressions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eusend-dev/openapi/eusend-dev-suppressions-api-openapi.yml
- filename: eusend-dev-system-api-openapi.yml
  format: yaml
  label: eusend-dev System API
  slug: eusend-dev-system-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eusend-dev/openapi/eusend-dev-system-api-openapi.yml
- filename: eusend-dev-templates-api-openapi.yml
  format: yaml
  label: eusend-dev Templates API
  slug: eusend-dev-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eusend-dev/openapi/eusend-dev-templates-api-openapi.yml
- filename: eusend-dev-topics-api-openapi.yml
  format: yaml
  label: eusend-dev Topics API
  slug: eusend-dev-topics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eusend-dev/openapi/eusend-dev-topics-api-openapi.yml
- filename: eusend-dev-webhooks-api-openapi.yml
  format: yaml
  label: eusend-dev Webhooks API
  slug: eusend-dev-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eusend-dev/openapi/eusend-dev-webhooks-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The service is available to businesses and to individuals.
    type: business
  - text: The service is available to businesses and to individuals.
    type: individual
  minimum_age:
    text: You must be at least 18 years old to create an account
    value: '18'
  restricted_uses:
  - summary: Unsolicited bulk email
    text: Send unsolicited bulk email (spam)
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
name: eusend-dev
provenance_date: '2026-11-09'
provider_name: eusend-dev
provider_slug: eusend-dev
slug: eusend-dev-eligibility
source_date: '2026-11-09'
source_filename: eusend-dev-eligibility.yml
source_heading: Eligibility
source_page: https://eusend.dev/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: eusend-dev\naid: eusend-dev\nurl: https://eusend.dev/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The service is available to businesses and to individuals.\n- type: individual\n  text: The service is available to businesses and to individuals.\nrestricted_uses:\n- summary: Unsolicited bulk email\n  text: Send unsolicited bulk email (spam)\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to create an account\n"
source_yaml_url: https://artifacts.apis.io/eusend-dev/eligibility/eusend-dev-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from eusend-dev's own page on 2026-11-09.
synthetic: false
tags:
- Email
- Transactional
- Marketing
- EU
- GDPR
---
