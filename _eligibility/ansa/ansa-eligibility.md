---
api_specs:
- filename: ansa-add-incentive-api-openapi.yml
  format: yaml
  label: Ansa Add Incentive API
  slug: ansa-add-incentive-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ansa/openapi/ansa-add-incentive-api-openapi.yml
- filename: ansa-customer-segments-api-openapi.yml
  format: yaml
  label: Ansa Customer Segments API
  slug: ansa-customer-segments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ansa/openapi/ansa-customer-segments-api-openapi.yml
- filename: ansa-customers-api-openapi.yml
  format: yaml
  label: Ansa Customers API
  slug: ansa-customers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ansa/openapi/ansa-customers-api-openapi.yml
- filename: ansa-initialize-payment-session-api-openapi.yml
  format: yaml
  label: Ansa Initialize Payment Session API
  slug: ansa-initialize-payment-session-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ansa/openapi/ansa-initialize-payment-session-api-openapi.yml
- filename: ansa-merchants-api-openapi.yml
  format: yaml
  label: Ansa Merchants API
  slug: ansa-merchants-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ansa/openapi/ansa-merchants-api-openapi.yml
- filename: ansa-refunds-api-openapi.yml
  format: yaml
  label: Ansa Refunds API
  slug: ansa-refunds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ansa/openapi/ansa-refunds-api-openapi.yml
- filename: ansa-transactions-api-openapi.yml
  format: yaml
  label: Ansa Transactions API
  slug: ansa-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ansa/openapi/ansa-transactions-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: You may only apply for an Account or use the Services if you are a legal entity formed and registered in the United States
  entity_types:
  - text: Only lawfully formed business entities are eligible to use Ansa Services.
    type: business
  - text: Individuals, consumers, or any non-commercial entities are not eligible to use Ansa Services.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Consumer or non-commercial purposes
    text: Any use of or access to the Services for consumer or non-commercial purposes, by anyone under 18, or by any individual who is not your employee, contractor, agent, or other authorized individual is strictly prohibited
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
name: Ansa
provenance_date: '2026-11-09'
provider_name: Ansa
provider_slug: ansa
slug: ansa-eligibility
source_date: '2026-11-09'
source_filename: ansa-eligibility.yml
source_heading: Eligibility
source_page: https://ansa.dev/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ansa\naid: ansa\nurl: https://ansa.dev/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: You may only apply for an Account or use the Services if you are a legal entity formed and registered in\n    the United States\nentity_types:\n- type: business\n  text: Only lawfully formed business entities are eligible to use Ansa Services.\n- type: individual\n  text: Individuals, consumers, or any non-commercial entities are not eligible to use Ansa Services.\nrestricted_uses:\n- summary: Consumer or non-commercial purposes\n  text: Any use of or access to the Services\
  \ for consumer or non-commercial purposes, by anyone under 18, or by\n    any individual who is not your employee, contractor, agent, or other authorized individual is strictly prohibited\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/ansa/eligibility/ansa-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from Ansa's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Payments
- Stored Value
- Digital Wallet
- Loyalty
- Incentives
- Loyalty & Incentives
---
