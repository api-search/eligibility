---
api_specs:
- filename: kanmon-bank-accounts-api-openapi.yml
  format: yaml
  label: Kanmon Bank Accounts API
  slug: kanmon-bank-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kanmon/openapi/kanmon-bank-accounts-api-openapi.yml
- filename: kanmon-businesses-api-openapi.yml
  format: yaml
  label: Kanmon Businesses API
  slug: kanmon-businesses-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kanmon/openapi/kanmon-businesses-api-openapi.yml
- filename: kanmon-connect-tokens-api-openapi.yml
  format: yaml
  label: Kanmon Connect Tokens API
  slug: kanmon-connect-tokens-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kanmon/openapi/kanmon-connect-tokens-api-openapi.yml
- filename: kanmon-documents-api-openapi.yml
  format: yaml
  label: Kanmon Documents API
  slug: kanmon-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kanmon/openapi/kanmon-documents-api-openapi.yml
- filename: kanmon-draw-requests-api-openapi.yml
  format: yaml
  label: Kanmon Draw Requests API
  slug: kanmon-draw-requests-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kanmon/openapi/kanmon-draw-requests-api-openapi.yml
- filename: kanmon-embedded-sessions-api-openapi.yml
  format: yaml
  label: Kanmon Embedded Sessions API
  slug: kanmon-embedded-sessions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kanmon/openapi/kanmon-embedded-sessions-api-openapi.yml
- filename: kanmon-integrated-mca-api-openapi.yml
  format: yaml
  label: Kanmon Integrated MCA API
  slug: kanmon-integrated-mca-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kanmon/openapi/kanmon-integrated-mca-api-openapi.yml
- filename: kanmon-invoices-api-openapi.yml
  format: yaml
  label: Kanmon Invoices API
  slug: kanmon-invoices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kanmon/openapi/kanmon-invoices-api-openapi.yml
- filename: kanmon-issued-products-api-openapi.yml
  format: yaml
  label: Kanmon Issued Products API
  slug: kanmon-issued-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kanmon/openapi/kanmon-issued-products-api-openapi.yml
- filename: kanmon-offers-api-openapi.yml
  format: yaml
  label: Kanmon Offers API
  slug: kanmon-offers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kanmon/openapi/kanmon-offers-api-openapi.yml
- filename: kanmon-payments-api-openapi.yml
  format: yaml
  label: Kanmon Payments API
  slug: kanmon-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kanmon/openapi/kanmon-payments-api-openapi.yml
- filename: kanmon-prequalifications-api-openapi.yml
  format: yaml
  label: Kanmon Prequalifications API
  slug: kanmon-prequalifications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kanmon/openapi/kanmon-prequalifications-api-openapi.yml
- filename: kanmon-sandbox-utilities-api-openapi.yml
  format: yaml
  label: Kanmon Sandbox Utilities API
  slug: kanmon-sandbox-utilities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kanmon/openapi/kanmon-sandbox-utilities-api-openapi.yml
- filename: kanmon-users-api-openapi.yml
  format: yaml
  label: Kanmon Users API
  slug: kanmon-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kanmon/openapi/kanmon-users-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Website and related services are intended solely for Users who are eighteen (18) years of age or older.
    type: individual
  minimum_age:
    text: The Website and related services are intended solely for Users who are eighteen (18) years of age or older.
    value: '18'
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
name: Kanmon
provenance_date: '2026-11-09'
provider_name: Kanmon
provider_slug: kanmon
slug: kanmon-eligibility
source_date: '2026-11-09'
source_filename: kanmon-eligibility.yml
source_heading: Eligibility
source_page: http://kanmon.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Kanmon\naid: kanmon\nurl: http://kanmon.com/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Website and related services are intended solely for Users who are eighteen (18) years of age or older.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Website and related services are intended solely for Users who are eighteen (18) years of age or older.\n"
source_yaml_url: https://artifacts.apis.io/kanmon/eligibility/kanmon-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from Kanmon's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Embedded Finance
- Embedded Lending
- Lending
- Working Capital
- Invoice Financing
---
