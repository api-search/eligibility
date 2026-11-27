---
api_specs:
- filename: treasury-prime-accounts-api-openapi.yml
  format: yaml
  label: Treasury Prime Accounts API
  slug: treasury-prime-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/treasury-prime/openapi/treasury-prime-accounts-api-openapi.yml
- filename: treasury-prime-businesses-api-openapi.yml
  format: yaml
  label: Treasury Prime Businesses API
  slug: treasury-prime-businesses-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/treasury-prime/openapi/treasury-prime-businesses-api-openapi.yml
- filename: treasury-prime-cards-api-openapi.yml
  format: yaml
  label: Treasury Prime Cards API
  slug: treasury-prime-cards-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/treasury-prime/openapi/treasury-prime-cards-api-openapi.yml
- filename: treasury-prime-health-api-openapi.yml
  format: yaml
  label: Treasury Prime Health API
  slug: treasury-prime-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/treasury-prime/openapi/treasury-prime-health-api-openapi.yml
- filename: treasury-prime-payments-api-openapi.yml
  format: yaml
  label: Treasury Prime Payments API
  slug: treasury-prime-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/treasury-prime/openapi/treasury-prime-payments-api-openapi.yml
- filename: treasury-prime-persons-api-openapi.yml
  format: yaml
  label: Treasury Prime Persons API
  slug: treasury-prime-persons-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/treasury-prime/openapi/treasury-prime-persons-api-openapi.yml
- filename: treasury-prime-statements-api-openapi.yml
  format: yaml
  label: Treasury Prime Statements API
  slug: treasury-prime-statements-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/treasury-prime/openapi/treasury-prime-statements-api-openapi.yml
- filename: treasury-prime-transactions-api-openapi.yml
  format: yaml
  label: Treasury Prime Transactions API
  slug: treasury-prime-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/treasury-prime/openapi/treasury-prime-transactions-api-openapi.yml
- filename: treasury-prime-webhooks-api-openapi.yml
  format: yaml
  label: Treasury Prime Webhooks API
  slug: treasury-prime-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/treasury-prime/openapi/treasury-prime-webhooks-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Service may not be appropriate or available for use in some non-U.S. jurisdictions.
  entity_types:
  - text: If you received a User ID with access to the client portion of the Service, you are accepting these Terms on behalf of yourself and the company for which Treasury Prime authorized your access to the Service.
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
name: Treasury Prime
provenance_date: '2026-11-10'
provider_name: Treasury Prime
provider_slug: treasury-prime
slug: treasury-prime-eligibility
source_date: '2026-11-10'
source_filename: treasury-prime-eligibility.yml
source_heading: Eligibility
source_page: https://www.treasuryprime.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Treasury Prime\naid: treasury-prime\nurl: https://www.treasuryprime.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Service may not be appropriate or available for use in some non-U.S. jurisdictions.\nentity_types:\n- type: business\n  text: If you received a User ID with access to the client portion of the Service, you are accepting these Terms\n    on behalf of yourself and the company for which Treasury Prime authorized your access to the Service.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/treasury-prime/eligibility/treasury-prime-eligibility.yml
stated_fields:
- countries
- entity_types
summary_line: 2 quoted statements, read from Treasury Prime's own page on 2026-11-10.
synthetic: false
tags:
- Fintech
- Banking as a Service
- Banking
- Payments
- Card Issuing
- ACH
- Embedded Finance
---
