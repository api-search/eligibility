---
api_specs:
- filename: bitoasis-market-data-api-openapi.yml
  format: yaml
  label: BitOasis Market Data API
  slug: bitoasis-market-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bitoasis/openapi/bitoasis-market-data-api-openapi.yml
- filename: bitoasis-accounts-api-openapi.yml
  format: yaml
  label: BitOasis Accounts API
  slug: bitoasis-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bitoasis/openapi/bitoasis-accounts-api-openapi.yml
- filename: bitoasis-banks-api-openapi.yml
  format: yaml
  label: BitOasis Banks API
  slug: bitoasis-banks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bitoasis/openapi/bitoasis-banks-api-openapi.yml
- filename: bitoasis-deposit-api-openapi.yml
  format: yaml
  label: BitOasis Deposit API
  slug: bitoasis-deposit-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bitoasis/openapi/bitoasis-deposit-api-openapi.yml
- filename: bitoasis-error-responses-api-openapi.yml
  format: yaml
  label: BitOasis Error responses API
  slug: bitoasis-error-responses-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bitoasis/openapi/bitoasis-error-responses-api-openapi.yml
- filename: bitoasis-order-api-openapi.yml
  format: yaml
  label: BitOasis Order API
  slug: bitoasis-order-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bitoasis/openapi/bitoasis-order-api-openapi.yml
- filename: bitoasis-withdrawal-api-openapi.yml
  format: yaml
  label: BitOasis Withdrawal API
  slug: bitoasis-withdrawal-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bitoasis/openapi/bitoasis-withdrawal-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: if you are an individual, that you are over eighteen years of age or have attained the age of majority as per applicable law
    type: individual
  - text: if you are registering on behalf of any entity, that you are authorized to enter into, and bind the entity to, these Terms
    type: business
  minimum_age:
    text: over eighteen years of age or have attained the age of majority as per applicable law
    value: '18'
  restricted_uses:
  - summary: No resale or commercial use
    text: You are prohibited to use the Services for resale or commercial purposes, including transactions on behalf of other persons or entities.
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: In order to access any Services, you must activate your account (“User Account”) by following the identity verification process of Know Your Customer (“KYC”)
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: BitOasis
provenance_date: '2026-11-09'
provider_name: BitOasis
provider_slug: bitoasis
slug: bitoasis-eligibility
source_date: '2026-11-09'
source_filename: bitoasis-eligibility.yml
source_heading: Eligibility
source_page: https://bitoasis.net/en/page/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BitOasis\naid: bitoasis\nurl: https://bitoasis.net/en/page/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: if you are an individual, that you are over eighteen years of age or have attained the age of majority as\n    per applicable law\n- type: business\n  text: if you are registering on behalf of any entity, that you are authorized to enter into, and bind the entity\n    to, these Terms\nrestricted_uses:\n- summary: No resale or commercial use\n  text: You are prohibited to use the Services for resale or commercial\
  \ purposes, including transactions on behalf\n    of other persons or entities.\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: In order to access any Services, you must activate your account (“User Account”) by following the identity\n    verification process of Know Your Customer (“KYC”)\nminimum_age:\n  value: '18'\n  text: over eighteen years of age or have attained the age of majority as per applicable law\n"
source_yaml_url: https://artifacts.apis.io/bitoasis/eligibility/bitoasis-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from BitOasis's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Cryptocurrency
- Exchange
- Trading
- Digital Assets
- Bitcoin
- MENA
- Fintech
- MCP
---
