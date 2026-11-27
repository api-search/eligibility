---
api_specs:
- filename: palla-accounts-api-openapi.yml
  format: yaml
  label: Palla Accounts API
  slug: palla-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/palla/openapi/palla-accounts-api-openapi.yml
- filename: palla-auth-api-openapi.yml
  format: yaml
  label: Palla Auth API
  slug: palla-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/palla/openapi/palla-auth-api-openapi.yml
- filename: palla-health-api-openapi.yml
  format: yaml
  label: Palla Health API
  slug: palla-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/palla/openapi/palla-health-api-openapi.yml
- filename: palla-links-api-openapi.yml
  format: yaml
  label: Palla Links API
  slug: palla-links-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/palla/openapi/palla-links-api-openapi.yml
- filename: palla-payment-methods-api-openapi.yml
  format: yaml
  label: Palla Payment Methods API
  slug: palla-payment-methods-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/palla/openapi/palla-payment-methods-api-openapi.yml
- filename: palla-relationships-api-openapi.yml
  format: yaml
  label: Palla Relationships API
  slug: palla-relationships-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/palla/openapi/palla-relationships-api-openapi.yml
- filename: palla-transfers-api-openapi.yml
  format: yaml
  label: Palla Transfers API
  slug: palla-transfers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/palla/openapi/palla-transfers-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Terms of Use that govern individuals who use Palla-powered sites and apps to send money abroad, for personal, family, or household purposes.
    type: individual
  - text: The Services Terms that govern companies using the Palla API and user interfaces to offer transfers to their own customers.
    type: business
  minimum_age:
    text: null
    value: null
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
name: Palla
provenance_date: '2026-11-10'
provider_name: Palla
provider_slug: palla
slug: palla-eligibility
source_date: '2026-11-10'
source_filename: palla-eligibility.yml
source_heading: Eligibility
source_page: https://www.palla.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Palla\naid: palla\nurl: https://www.palla.com/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Terms of Use that govern individuals who use Palla-powered sites and apps to send money abroad, for\n    personal, family, or household purposes.\n- type: business\n  text: The Services Terms that govern companies using the Palla API and user interfaces to offer transfers to their\n    own customers.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/palla/eligibility/palla-eligibility.yml
stated_fields:
- entity_types
summary_line: 2 quoted statements, read from Palla's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fintech
- Payments
- Cross-Border Payments
- Remittances
- P2P Payments
- Money Transfer
- Embedded Finance
---
