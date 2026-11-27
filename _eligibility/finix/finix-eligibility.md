---
api_specs:
- filename: finix-authorizations-api-openapi.yml
  format: yaml
  label: Finix Authorizations API
  slug: finix-authorizations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/finix/openapi/finix-authorizations-api-openapi.yml
- filename: finix-balance-transfers-api-openapi.yml
  format: yaml
  label: Finix Balance Transfers API
  slug: finix-balance-transfers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/finix/openapi/finix-balance-transfers-api-openapi.yml
- filename: finix-compliance-forms-api-openapi.yml
  format: yaml
  label: Finix Compliance Forms API
  slug: finix-compliance-forms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/finix/openapi/finix-compliance-forms-api-openapi.yml
- filename: finix-devices-api-openapi.yml
  format: yaml
  label: Finix Devices API
  slug: finix-devices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/finix/openapi/finix-devices-api-openapi.yml
- filename: finix-disputes-api-openapi.yml
  format: yaml
  label: Finix Disputes API
  slug: finix-disputes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/finix/openapi/finix-disputes-api-openapi.yml
- filename: finix-fee-profiles-api-openapi.yml
  format: yaml
  label: Finix Fee Profiles API
  slug: finix-fee-profiles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/finix/openapi/finix-fee-profiles-api-openapi.yml
- filename: finix-files-api-openapi.yml
  format: yaml
  label: Finix Files API
  slug: finix-files-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/finix/openapi/finix-files-api-openapi.yml
- filename: finix-identities-api-openapi.yml
  format: yaml
  label: Finix Identities API
  slug: finix-identities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/finix/openapi/finix-identities-api-openapi.yml
- filename: finix-instrument-updates-api-openapi.yml
  format: yaml
  label: Finix Instrument Updates API
  slug: finix-instrument-updates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/finix/openapi/finix-instrument-updates-api-openapi.yml
- filename: finix-merchant-profiles-api-openapi.yml
  format: yaml
  label: Finix Merchant Profiles API
  slug: finix-merchant-profiles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/finix/openapi/finix-merchant-profiles-api-openapi.yml
- filename: finix-merchants-api-openapi.yml
  format: yaml
  label: Finix Merchants API
  slug: finix-merchants-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/finix/openapi/finix-merchants-api-openapi.yml
- filename: finix-onboarding-forms-api-openapi.yml
  format: yaml
  label: Finix Onboarding Forms API
  slug: finix-onboarding-forms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/finix/openapi/finix-onboarding-forms-api-openapi.yml
- filename: finix-payment-instruments-api-openapi.yml
  format: yaml
  label: Finix Payment Instruments API
  slug: finix-payment-instruments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/finix/openapi/finix-payment-instruments-api-openapi.yml
- filename: finix-payout-profiles-api-openapi.yml
  format: yaml
  label: Finix Payout Profiles API
  slug: finix-payout-profiles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/finix/openapi/finix-payout-profiles-api-openapi.yml
- filename: finix-settlements-api-openapi.yml
  format: yaml
  label: Finix Settlements API
  slug: finix-settlements-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/finix/openapi/finix-settlements-api-openapi.yml
- filename: finix-split-transfers-api-openapi.yml
  format: yaml
  label: Finix Split Transfers API
  slug: finix-split-transfers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/finix/openapi/finix-split-transfers-api-openapi.yml
- filename: finix-transfers-api-openapi.yml
  format: yaml
  label: Finix Transfers API
  slug: finix-transfers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/finix/openapi/finix-transfers-api-openapi.yml
- filename: finix-verifications-api-openapi.yml
  format: yaml
  label: Finix Verifications API
  slug: finix-verifications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/finix/openapi/finix-verifications-api-openapi.yml
- filename: finix-webhooks-api-openapi.yml
  format: yaml
  label: Finix Webhooks API
  slug: finix-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/finix/openapi/finix-webhooks-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    - CA
    text: Finix Payments, Inc. operates in the United States. Finix Canada, Inc. operates in Canada.
  entity_types:
  - text: provide payment processing services and related tools to businesses.
    type: business
  minimum_age:
    text: Our services are not directed to individuals under the age of 18, and we do not knowingly collect personal information from minors.
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
name: Finix
provenance_date: '2026-11-09'
provider_name: Finix
provider_slug: finix
slug: finix-eligibility
source_date: '2026-11-09'
source_filename: finix-eligibility.yml
source_heading: Eligibility
source_page: https://finix.com/terms-and-policies
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Finix\naid: finix\nurl: https://finix.com/terms-and-policies\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  - CA\n  excluded: []\n  text: Finix Payments, Inc. operates in the United States. Finix Canada, Inc. operates in Canada.\nentity_types:\n- type: business\n  text: provide payment processing services and related tools to businesses.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Our services are not directed to individuals under the age of 18, and we do not knowingly collect personal\n    information\
  \ from minors.\n"
source_yaml_url: https://artifacts.apis.io/finix/eligibility/finix-eligibility.yml
stated_fields:
- countries
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from Finix's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Payments
- Payment Processing
- Payment Facilitation
- Merchant Onboarding
- Payouts
- Marketplace
- Embedded Finance
- ACH
- Card Acceptance
- PCI DSS
---
