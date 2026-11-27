---
api_specs:
- filename: past-dev-audiences-api-openapi.yml
  format: yaml
  label: past-dev Audiences API
  slug: past-dev-audiences-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/past-dev/openapi/past-dev-audiences-api-openapi.yml
- filename: past-dev-debugging-api-openapi.yml
  format: yaml
  label: past-dev Debugging API
  slug: past-dev-debugging-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/past-dev/openapi/past-dev-debugging-api-openapi.yml
- filename: past-dev-identities-api-openapi.yml
  format: yaml
  label: past-dev Identities API
  slug: past-dev-identities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/past-dev/openapi/past-dev-identities-api-openapi.yml
- filename: past-dev-ingestion-api-openapi.yml
  format: yaml
  label: past-dev Ingestion API
  slug: past-dev-ingestion-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/past-dev/openapi/past-dev-ingestion-api-openapi.yml
- filename: past-dev-management-api-openapi.yml
  format: yaml
  label: past-dev Management API
  slug: past-dev-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/past-dev/openapi/past-dev-management-api-openapi.yml
- filename: past-dev-recall-api-openapi.yml
  format: yaml
  label: past-dev Recall API
  slug: past-dev-recall-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/past-dev/openapi/past-dev-recall-api-openapi.yml
- filename: past-dev-webhooks-api-openapi.yml
  format: yaml
  label: past-dev Webhooks API
  slug: past-dev-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/past-dev/openapi/past-dev-webhooks-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Do not use the service from a country under a United States embargo, or if you are on a United States sanctions list.
  entity_types:
  - text: If you act for a company, you confirm you may bind it, and "you" means that company.
    type: business
  minimum_age:
    text: You must be at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: Embargoed countries and sanctioned persons
    text: Do not use the service from a country under a United States embargo, or if you are on a United States sanctions list.
  verification:
    approval_required: false
    kyb: null
    kyc: null
    text: 'Nobody approves an account: it exists once sign-up is complete.'
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: past-dev
provenance_date: '2026-11-10'
provider_name: past-dev
provider_slug: past-dev
slug: past-dev-eligibility
source_date: '2026-11-10'
source_filename: past-dev-eligibility.yml
source_heading: Eligibility
source_page: https://past.dev/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: past-dev\naid: past-dev\nurl: https://past.dev/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Do not use the service from a country under a United States embargo, or if you are on a United States sanctions\n    list.\nentity_types:\n- type: business\n  text: If you act for a company, you confirm you may bind it, and \"you\" means that company.\nrestricted_uses:\n- summary: Embargoed countries and sanctioned persons\n  text: Do not use the service from a country under a United States embargo, or if you are on a United States sanctions\n    list.\nverification:\n  kyc: null\n\
  \  kyb: null\n  approval_required: false\n  text: 'Nobody approves an account: it exists once sign-up is complete.'\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/past-dev/eligibility/past-dev-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from past-dev's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- Memory
- Platform
- Developers
---
