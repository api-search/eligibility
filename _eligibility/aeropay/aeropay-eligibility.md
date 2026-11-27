---
api_specs:
- filename: aeropay-authentication-api-openapi.yml
  format: yaml
  label: Aeropay Authentication API
  slug: aeropay-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aeropay/openapi/aeropay-authentication-api-openapi.yml
- filename: aeropay-bank-connection-api-openapi.yml
  format: yaml
  label: Aeropay Bank Connection API
  slug: aeropay-bank-connection-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aeropay/openapi/aeropay-bank-connection-api-openapi.yml
- filename: aeropay-create-manage-transactions-api-openapi.yml
  format: yaml
  label: Aeropay Create & Manage Transactions API
  slug: aeropay-create-manage-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aeropay/openapi/aeropay-create-manage-transactions-api-openapi.yml
- filename: aeropay-merchant-management-api-openapi.yml
  format: yaml
  label: Aeropay Merchant Management API
  slug: aeropay-merchant-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aeropay/openapi/aeropay-merchant-management-api-openapi.yml
- filename: aeropay-reports-api-openapi.yml
  format: yaml
  label: Aeropay Reports API
  slug: aeropay-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aeropay/openapi/aeropay-reports-api-openapi.yml
- filename: aeropay-user-management-api-openapi.yml
  format: yaml
  label: Aeropay User Management API
  slug: aeropay-user-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aeropay/openapi/aeropay-user-management-api-openapi.yml
- filename: aeropay-webhooks-api-openapi.yml
  format: yaml
  label: Aeropay Webhooks API
  slug: aeropay-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aeropay/openapi/aeropay-webhooks-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: 'you may be required to provide information ... including but not limited to: a valid US physical address (not including P.O. Boxes or commercial mail receiving agencies)'
  entity_types:
  - text: Aeropay offers Personal, Business and Non-profit accounts (each an “Account”).
    type: individual
  - text: If you open a Business or Non-profit Account, you agree that you are not opening the Account primarily for personal, family, or household purposes.
    type: business
  - text: Aeropay offers Personal, Business and Non-profit accounts (each an “Account”).
    type: nonprofit
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Activities requiring consent
    text: 'Engage in the following activities without Aeropay’s prior written consent: transactions related to online gambling, or activities regulated by FinCEN, including money services business activities and payday lending;'
  - summary: Restricted categories
    text: (xi) Payday lenders, their owners and principals; and (xii) Missions, embassies and consulates.
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
name: Aeropay
provenance_date: '2026-11-09'
provider_name: Aeropay
provider_slug: aeropay
slug: aeropay-eligibility
source_date: '2026-11-09'
source_filename: aeropay-eligibility.yml
source_heading: Eligibility
source_page: https://www.aeropay.com/legal/terms-of-service---merchant
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Aeropay\naid: aeropay\nurl: https://www.aeropay.com/legal/terms-of-service---merchant\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: 'you may be required to provide information ... including but not limited to: a valid US physical address\n    (not including P.O. Boxes or commercial mail receiving agencies)'\nentity_types:\n- type: individual\n  text: Aeropay offers Personal, Business and Non-profit accounts (each an “Account”).\n- type: business\n  text: If you open a Business or Non-profit Account, you agree that you are not opening the Account primarily for\n    personal,\
  \ family, or household purposes.\n- type: nonprofit\n  text: Aeropay offers Personal, Business and Non-profit accounts (each an “Account”).\nrestricted_uses:\n- summary: Activities requiring consent\n  text: 'Engage in the following activities without Aeropay’s prior written consent: transactions related to online\n    gambling, or activities regulated by FinCEN, including money services business activities and payday lending;'\n- summary: Restricted categories\n  text: (xi) Payday lenders, their owners and principals; and (xii) Missions, embassies and consulates.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/aeropay/eligibility/aeropay-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 6 quoted statements, read from Aeropay's own page on 2026-11-09.
synthetic: false
tags:
- Payments
- Pay by Bank
- ACH
- Open Banking
- Fintech
- Bank linking
- Financial Services
- Real-Time Payments
- Webhook
- Payouts
- MCP
- Risk & fraud
---
