---
api_specs:
- filename: keycorp-account-information-api-openapi.yml
  format: yaml
  label: KeyCorp Account Information API
  slug: keycorp-account-information-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/keycorp/openapi/keycorp-account-information-api-openapi.yml
- filename: keycorp-account-transactions-api-openapi.yml
  format: yaml
  label: KeyCorp Account Transactions API
  slug: keycorp-account-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/keycorp/openapi/keycorp-account-transactions-api-openapi.yml
- filename: keycorp-accounts-api-openapi.yml
  format: yaml
  label: KeyCorp Accounts API
  slug: keycorp-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/keycorp/openapi/keycorp-accounts-api-openapi.yml
- filename: keycorp-ach-api-openapi.yml
  format: yaml
  label: KeyCorp ACH API
  slug: keycorp-ach-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/keycorp/openapi/keycorp-ach-api-openapi.yml
- filename: keycorp-ach-payment-origination-api-openapi.yml
  format: yaml
  label: KeyCorp ACH Payment Origination API
  slug: keycorp-ach-payment-origination-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/keycorp/openapi/keycorp-ach-payment-origination-api-openapi.yml
- filename: keycorp-ach-payment-request-inquiry-api-openapi.yml
  format: yaml
  label: KeyCorp ACH Payment Request Inquiry API
  slug: keycorp-ach-payment-request-inquiry-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/keycorp/openapi/keycorp-ach-payment-request-inquiry-api-openapi.yml
- filename: keycorp-ach-transactions-api-openapi.yml
  format: yaml
  label: KeyCorp ACH Transactions API
  slug: keycorp-ach-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/keycorp/openapi/keycorp-ach-transactions-api-openapi.yml
- filename: keycorp-imagecheck-api-openapi.yml
  format: yaml
  label: KeyCorp Image Check API
  slug: keycorp-imagecheck-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/keycorp/openapi/keycorp-imagecheck-api-openapi.yml
- filename: keycorp-initiate-api-openapi.yml
  format: yaml
  label: KeyCorp Initiate API
  slug: keycorp-initiate-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/keycorp/openapi/keycorp-initiate-api-openapi.yml
- filename: keycorp-participant-api-openapi.yml
  format: yaml
  label: KeyCorp Participant API
  slug: keycorp-participant-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/keycorp/openapi/keycorp-participant-api-openapi.yml
- filename: keycorp-rtp-api-openapi.yml
  format: yaml
  label: KeyCorp RTP API
  slug: keycorp-rtp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/keycorp/openapi/keycorp-rtp-api-openapi.yml
- filename: keycorp-stoppayments-api-openapi.yml
  format: yaml
  label: KeyCorp Stop Payments API
  slug: keycorp-stoppayments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/keycorp/openapi/keycorp-stoppayments-api-openapi.yml
- filename: keycorp-undo-ach-payment-request-api-openapi.yml
  format: yaml
  label: KeyCorp Undo ACH Payment Request API
  slug: keycorp-undo-ach-payment-request-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/keycorp/openapi/keycorp-undo-ach-payment-request-api-openapi.yml
- filename: keycorp-validate-api-openapi.yml
  format: yaml
  label: KeyCorp Validate API
  slug: keycorp-validate-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/keycorp/openapi/keycorp-validate-api-openapi.yml
- filename: keycorp-wire-api-openapi.yml
  format: yaml
  label: KeyCorp Wire API
  slug: keycorp-wire-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/keycorp/openapi/keycorp-wire-api-openapi.yml
- filename: keycorp-wire-rtp-v1-api-openapi.yml
  format: yaml
  label: KeyCorp Wire/RTP v1 API
  slug: keycorp-wire-rtp-v1-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/keycorp/openapi/keycorp-wire-rtp-v1-api-openapi.yml
- filename: keycorp-wire-rtp-v2-api-openapi.yml
  format: yaml
  label: KeyCorp Wire/RTP v2 API
  slug: keycorp-wire-rtp-v2-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/keycorp/openapi/keycorp-wire-rtp-v2-api-openapi.yml
- filename: keycorp-health-check-api-openapi.yml
  format: yaml
  label: KeyCorp Health Check API
  slug: keycorp-health-check-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/keycorp/openapi/keycorp-health-check-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - LR
    - MM
    - KP
    - SD
    - SY
    served: []
    text: 'Bank will restrict the availability of the Service during the time when you are in the following countries: Cuba, Iran, Liberia, Myanmar/Burma, North Korea, Sudan, and Syria'
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Prohibited illegal or improper activity
    text: You will not use the Service, or any financial service or product provided by Bank, for any illegal, fraudulent, unauthorized, or improper activity
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You will be required to register and create Login Credentials to use all or part of the Service.
excluded_countries:
- CU
- IR
- LR
- MM
- KP
- SD
- SY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: KeyCorp
provenance_date: '2026-11-09'
provider_name: KeyCorp
provider_slug: keycorp
slug: keycorp-eligibility
source_date: '2026-11-09'
source_filename: keycorp-eligibility.yml
source_heading: Eligibility
source_page: https://developer.key.com/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: KeyCorp\naid: keycorp\nurl: https://developer.key.com/tos\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - LR\n  - MM\n  - KP\n  - SD\n  - SY\n  text: 'Bank will restrict the availability of the Service during the time when you are in the following countries:\n    Cuba, Iran, Liberia, Myanmar/Burma, North Korea, Sudan, and Syria'\nentity_types: []\nrestricted_uses:\n- summary: Prohibited illegal or improper activity\n  text: You will not use the Service, or any financial service or product provided by Bank, for any illegal, fraudulent,\n    unauthorized, or improper activity\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You will be required to register and create Login Credentials to use all or part of the Service.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/keycorp/eligibility/keycorp-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
summary_line: 3 quoted statements, read from KeyCorp's own page on 2026-11-09.
synthetic: false
tags:
- Banking
- Commercial Banking
- Financial Services
- Fortune 500
- Payments
- United States
- Super-Regional Bank
- Treasury Management
- Embedded Banking
- ACH
- Real-Time Payments
- Wire Transfers
---
