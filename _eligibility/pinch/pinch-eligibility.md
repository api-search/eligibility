---
api_specs:
- filename: pinch-openapi-generated.yml
  format: yaml
  label: Pinch API
  slug: pinch-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pinch/openapi/_ae-authored/pinch-openapi-generated.yml
- filename: pinch-calculate-fees-api-openapi.yml
  format: yaml
  label: Pinch Calculate Fees API
  slug: pinch-calculate-fees-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pinch/openapi/pinch-calculate-fees-api-openapi.yml
- filename: pinch-connect-api-openapi.yml
  format: yaml
  label: Pinch Connect API
  slug: pinch-connect-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pinch/openapi/pinch-connect-api-openapi.yml
- filename: pinch-fees-api-openapi.yml
  format: yaml
  label: Pinch Fees API
  slug: pinch-fees-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pinch/openapi/pinch-fees-api-openapi.yml
- filename: pinch-merchants-api-openapi.yml
  format: yaml
  label: Pinch Merchants API
  slug: pinch-merchants-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pinch/openapi/pinch-merchants-api-openapi.yml
- filename: pinch-payers-api-openapi.yml
  format: yaml
  label: Pinch Payers API
  slug: pinch-payers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pinch/openapi/pinch-payers-api-openapi.yml
- filename: pinch-payment-links-api-openapi.yml
  format: yaml
  label: Pinch Payment Links API
  slug: pinch-payment-links-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pinch/openapi/pinch-payment-links-api-openapi.yml
- filename: pinch-payments-api-openapi.yml
  format: yaml
  label: Pinch Payments API
  slug: pinch-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pinch/openapi/pinch-payments-api-openapi.yml
- filename: pinch-plans-api-openapi.yml
  format: yaml
  label: Pinch Plans API
  slug: pinch-plans-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pinch/openapi/pinch-plans-api-openapi.yml
- filename: pinch-refund-api-openapi.yml
  format: yaml
  label: Pinch Refund API
  slug: pinch-refund-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pinch/openapi/pinch-refund-api-openapi.yml
- filename: pinch-refunds-api-openapi.yml
  format: yaml
  label: Pinch Refunds API
  slug: pinch-refunds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pinch/openapi/pinch-refunds-api-openapi.yml
- filename: pinch-sources-api-openapi.yml
  format: yaml
  label: Pinch Sources API
  slug: pinch-sources-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pinch/openapi/pinch-sources-api-openapi.yml
- filename: pinch-subscriptions-api-openapi.yml
  format: yaml
  label: Pinch Subscriptions API
  slug: pinch-subscriptions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pinch/openapi/pinch-subscriptions-api-openapi.yml
- filename: pinch-test-api-openapi.yml
  format: yaml
  label: Pinch Test API
  slug: pinch-test-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pinch/openapi/pinch-test-api-openapi.yml
- filename: pinch-transfers-api-openapi.yml
  format: yaml
  label: Pinch Transfers API
  slug: pinch-transfers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pinch/openapi/pinch-transfers-api-openapi.yml
- filename: pinch-webhooks-api-openapi.yml
  format: yaml
  label: Pinch Webhooks API
  slug: pinch-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pinch/openapi/pinch-webhooks-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Site and the services offered through it are intended for adults who are 18 years of age or older and who reside in the United States.
  entity_types:
  - text: The Site and the services offered through it are intended for adults who are 18 years of age or older and who reside in the United States.
    type: individual
  minimum_age:
    text: intended for adults who are 18 years of age or older
    value: '18'
  restricted_uses:
  - summary: False information to obtain services
    text: Providing false or misleading health, identity, age, or location information in order to obtain services or medications
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: In-person services are available only in the markets where Pinch Providers are licensed and active, and the telehealth program is available only in the states where our independent, third-party telehealth platform provider operates.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Pinch
provenance_date: '2026-11-10'
provider_name: Pinch
provider_slug: pinch
slug: pinch-eligibility
source_date: '2026-11-10'
source_filename: pinch-eligibility.yml
source_heading: Eligibility
source_page: https://www.bookpinch.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Pinch\naid: pinch\nurl: https://www.bookpinch.com/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Site and the services offered through it are intended for adults who are 18 years of age or older and\n    who reside in the United States.\nentity_types:\n- type: individual\n  text: The Site and the services offered through it are intended for adults who are 18 years of age or older and\n    who reside in the United States.\nrestricted_uses:\n- summary: False information to obtain services\n  text: Providing false or misleading health, identity, age, or location\
  \ information in order to obtain services\n    or medications\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: In-person services are available only in the markets where Pinch Providers are licensed and active, and\n    the telehealth program is available only in the states where our independent, third-party telehealth platform\n    provider operates.\nminimum_age:\n  value: '18'\n  text: intended for adults who are 18 years of age or older\n"
source_yaml_url: https://artifacts.apis.io/pinch/eligibility/pinch-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Pinch's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Payments
- Medical Spa
- Health Tech
---
