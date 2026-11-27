---
api_specs:
- filename: paystone-balance-portal-api-openapi.yml
  format: yaml
  label: Paystone Balance Portal API
  slug: paystone-balance-portal-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paystone/openapi/paystone-balance-portal-api-openapi.yml
- filename: paystone-client-management-api-openapi.yml
  format: yaml
  label: Paystone Client Management API
  slug: paystone-client-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paystone/openapi/paystone-client-management-api-openapi.yml
- filename: paystone-contact-api-openapi.yml
  format: yaml
  label: Paystone Contact API
  slug: paystone-contact-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paystone/openapi/paystone-contact-api-openapi.yml
- filename: paystone-gift-account-type-api-openapi.yml
  format: yaml
  label: Paystone Gift Account Type API
  slug: paystone-gift-account-type-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paystone/openapi/paystone-gift-account-type-api-openapi.yml
- filename: paystone-item-api-openapi.yml
  format: yaml
  label: Paystone Item API
  slug: paystone-item-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paystone/openapi/paystone-item-api-openapi.yml
- filename: paystone-loyalty-account-type-api-openapi.yml
  format: yaml
  label: Paystone Loyalty Account Type API
  slug: paystone-loyalty-account-type-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paystone/openapi/paystone-loyalty-account-type-api-openapi.yml
- filename: paystone-loyalty-transaction-api-openapi.yml
  format: yaml
  label: Paystone Loyalty Transaction API
  slug: paystone-loyalty-transaction-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paystone/openapi/paystone-loyalty-transaction-api-openapi.yml
- filename: paystone-member-portal-api-openapi.yml
  format: yaml
  label: Paystone Member Portal API
  slug: paystone-member-portal-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paystone/openapi/paystone-member-portal-api-openapi.yml
- filename: paystone-merchant-management-api-openapi.yml
  format: yaml
  label: Paystone Merchant Management API
  slug: paystone-merchant-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paystone/openapi/paystone-merchant-management-api-openapi.yml
- filename: paystone-prepaid-transaction-api-openapi.yml
  format: yaml
  label: Paystone Prepaid Transaction API
  slug: paystone-prepaid-transaction-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paystone/openapi/paystone-prepaid-transaction-api-openapi.yml
- filename: paystone-promo-account-type-api-openapi.yml
  format: yaml
  label: Paystone Promo Account Type API
  slug: paystone-promo-account-type-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paystone/openapi/paystone-promo-account-type-api-openapi.yml
- filename: paystone-reward-api-openapi.yml
  format: yaml
  label: Paystone Reward API
  slug: paystone-reward-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paystone/openapi/paystone-reward-api-openapi.yml
- filename: paystone-user-management-api-openapi.yml
  format: yaml
  label: Paystone User Management API
  slug: paystone-user-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paystone/openapi/paystone-user-management-api-openapi.yml
- filename: paystone-webhook-management-api-openapi.yml
  format: yaml
  label: Paystone Webhook Management API
  slug: paystone-webhook-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paystone/openapi/paystone-webhook-management-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: While we are a Canadian company and store data in Canada, the United States, and the European Union when providing our Services to users around the world.
  entity_types:
  - text: the merchant(s) (the "Merchant" ) whose information appears on the Application
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: bona fide sales only
    text: process transactions for only bona fide sales of goods and/or services
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: The provision of the Services is conditional on the acceptance of the Merchant by Paystone and/or a Payment Acquirer associated with Paystone.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Paystone
provenance_date: '2026-11-10'
provider_name: Paystone
provider_slug: paystone
slug: paystone-eligibility
source_date: '2026-11-10'
source_filename: paystone-eligibility.yml
source_heading: Eligibility
source_page: https://www.paystone.com/legal
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Paystone\naid: paystone\nurl: https://www.paystone.com/legal\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: While we are a Canadian company and store data in Canada, the United States, and the European Union when\n    providing our Services to users around the world.\nentity_types:\n- type: business\n  text: the merchant(s) (the \"Merchant\" ) whose information appears on the Application\nrestricted_uses:\n- summary: bona fide sales only\n  text: process transactions for only bona fide sales of goods and/or services\nverification:\n  kyc: null\n  kyb: null\n \
  \ approval_required: true\n  text: The provision of the Services is conditional on the acceptance of the Merchant by Paystone and/or a Payment\n    Acquirer associated with Paystone.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/paystone/eligibility/paystone-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from Paystone's own page on 2026-11-10.
synthetic: false
tags:
- Payments
- Canada
- Payment Processing
- Acquiring
- Gift Cards
- Loyalty
- Subscription
- Billing
- Merchant Services
---
