---
api_specs:
- filename: ntropy-account-holder-api-openapi.yml
  format: yaml
  label: Ntropy Account Holder API
  slug: ntropy-account-holder-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ntropy/openapi/ntropy-account-holder-api-openapi.yml
- filename: ntropy-bank-statements-api-openapi.yml
  format: yaml
  label: Ntropy Bank statements API
  slug: ntropy-bank-statements-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ntropy/openapi/ntropy-bank-statements-api-openapi.yml
- filename: ntropy-batches-api-openapi.yml
  format: yaml
  label: Ntropy Batches API
  slug: ntropy-batches-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ntropy/openapi/ntropy-batches-api-openapi.yml
- filename: ntropy-categories-api-openapi.yml
  format: yaml
  label: Ntropy Categories API
  slug: ntropy-categories-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ntropy/openapi/ntropy-categories-api-openapi.yml
- filename: ntropy-enrichment-api-openapi.yml
  format: yaml
  label: Ntropy Enrichment API
  slug: ntropy-enrichment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ntropy/openapi/ntropy-enrichment-api-openapi.yml
- filename: ntropy-entities-api-openapi.yml
  format: yaml
  label: Ntropy Entities API
  slug: ntropy-entities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ntropy/openapi/ntropy-entities-api-openapi.yml
- filename: ntropy-labels-api-openapi.yml
  format: yaml
  label: Ntropy Labels API
  slug: ntropy-labels-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ntropy/openapi/ntropy-labels-api-openapi.yml
- filename: ntropy-misc-api-openapi.yml
  format: yaml
  label: Ntropy Misc API
  slug: ntropy-misc-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ntropy/openapi/ntropy-misc-api-openapi.yml
- filename: ntropy-personalization-api-openapi.yml
  format: yaml
  label: Ntropy Personalization API
  slug: ntropy-personalization-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ntropy/openapi/ntropy-personalization-api-openapi.yml
- filename: ntropy-recurrence-api-openapi.yml
  format: yaml
  label: Ntropy Recurrence API
  slug: ntropy-recurrence-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ntropy/openapi/ntropy-recurrence-api-openapi.yml
- filename: ntropy-reporting-api-openapi.yml
  format: yaml
  label: Ntropy Reporting API
  slug: ntropy-reporting-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ntropy/openapi/ntropy-reporting-api-openapi.yml
- filename: ntropy-reports-api-openapi.yml
  format: yaml
  label: Ntropy Reports API
  slug: ntropy-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ntropy/openapi/ntropy-reports-api-openapi.yml
- filename: ntropy-transactions-api-openapi.yml
  format: yaml
  label: Ntropy Transactions API
  slug: ntropy-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ntropy/openapi/ntropy-transactions-api-openapi.yml
- filename: ntropy-webhooks-api-openapi.yml
  format: yaml
  label: Ntropy Webhooks API
  slug: ntropy-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ntropy/openapi/ntropy-webhooks-api-openapi.yml
- filename: ntropy-account-holders-api-openapi.yml
  format: yaml
  label: Ntropy Account Holders API
  slug: ntropy-account-holders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ntropy/openapi/ntropy-account-holders-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded:
    - IR
    - SY
    - CU
    - SD
    - KP
    served:
    - US
    - GB
    text: 'You are authorized to permit your Affiliates specified in your registration that are located in the United States and United Kingdom only to access and use the Services. Export restriction: ''any country subject to an embargo or other sanction by the United States, including Iran, Syria, Cuba, Sudan and North Korea'''
  entity_types:
  - text: IF YOU ARE AN INDIVIDUAL ACCESSING OR USING THE SERVICES ON BEHALF OF, OR FOR THE BENEFIT OF, ANY CORPORATION, PARTNERSHIP OR OTHER ENTITY
    type: individual
  - text: ANY CORPORATION, PARTNERSHIP OR OTHER ENTITY WITH WHICH YOU ARE ASSOCIATED
    type: business
  minimum_age:
    text: AFFIRM THAT YOU ARE OF LEGAL AGE WHERE YOU LIVE AND HAVE THE LEGAL CAPACITY TO ENTER INTO THIS AGREEMENT.
    value: legal age where you live
  restricted_uses:
  - summary: export and sanctions compliance
    text: You and your Permitted Users will fully comply with all relevant export, import and sanction laws, rules and regulations of the United States and any other country
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- IR
- SY
- CU
- SD
- KP
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Ntropy
provenance_date: '2026-11-10'
provider_name: Ntropy
provider_slug: ntropy
slug: ntropy-eligibility
source_date: '2026-11-10'
source_filename: ntropy-eligibility.yml
source_heading: Eligibility
source_page: https://www.ntropy.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ntropy\naid: ntropy\nurl: https://www.ntropy.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  - GB\n  excluded:\n  - IR\n  - SY\n  - CU\n  - SD\n  - KP\n  text: 'You are authorized to permit your Affiliates specified in your registration that are located in the United\n    States and United Kingdom only to access and use the Services. Export restriction: ''any country subject to\n    an embargo or other sanction by the United States, including Iran, Syria, Cuba, Sudan and North Korea'''\nentity_types:\n- type: individual\n  text: IF YOU ARE AN INDIVIDUAL ACCESSING OR USING THE SERVICES ON\
  \ BEHALF OF, OR FOR THE BENEFIT OF, ANY CORPORATION,\n    PARTNERSHIP OR OTHER ENTITY\n- type: business\n  text: ANY CORPORATION, PARTNERSHIP OR OTHER ENTITY WITH WHICH YOU ARE ASSOCIATED\nrestricted_uses:\n- summary: export and sanctions compliance\n  text: You and your Permitted Users will fully comply with all relevant export, import and sanction laws, rules\n    and regulations of the United States and any other country\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: legal age where you live\n  text: AFFIRM THAT YOU ARE OF LEGAL AGE WHERE YOU LIVE AND HAVE THE LEGAL CAPACITY TO ENTER INTO THIS AGREEMENT.\n"
source_yaml_url: https://artifacts.apis.io/ntropy/eligibility/ntropy-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Ntropy's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fintech
- Transaction Enrichment
- Financial Data
- Data Enrichment
- Bank Statements
- Categorization
- Underwriting
---
