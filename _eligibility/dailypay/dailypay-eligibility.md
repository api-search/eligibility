---
api_specs:
- filename: dailypay-accounts-api-openapi.yml
  format: yaml
  label: DailyPay Accounts API
  slug: dailypay-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dailypay/openapi/dailypay-accounts-api-openapi.yml
- filename: dailypay-card-tokenization-api-openapi.yml
  format: yaml
  label: DailyPay Card Tokenization API
  slug: dailypay-card-tokenization-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dailypay/openapi/dailypay-card-tokenization-api-openapi.yml
- filename: dailypay-health-api-openapi.yml
  format: yaml
  label: DailyPay Health API
  slug: dailypay-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dailypay/openapi/dailypay-health-api-openapi.yml
- filename: dailypay-jobs-api-openapi.yml
  format: yaml
  label: DailyPay Jobs API
  slug: dailypay-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dailypay/openapi/dailypay-jobs-api-openapi.yml
- filename: dailypay-organizations-api-openapi.yml
  format: yaml
  label: DailyPay Organizations API
  slug: dailypay-organizations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dailypay/openapi/dailypay-organizations-api-openapi.yml
- filename: dailypay-paychecks-api-openapi.yml
  format: yaml
  label: DailyPay Paychecks API
  slug: dailypay-paychecks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dailypay/openapi/dailypay-paychecks-api-openapi.yml
- filename: dailypay-people-api-openapi.yml
  format: yaml
  label: DailyPay People API
  slug: dailypay-people-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dailypay/openapi/dailypay-people-api-openapi.yml
- filename: dailypay-transfers-api-openapi.yml
  format: yaml
  label: DailyPay Transfers API
  slug: dailypay-transfers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dailypay/openapi/dailypay-transfers-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You represent and warrant that (A) you are not located in a country that is subject to a U.S. government embargo or that has been designated by the U.S. government as a "terrorist supporting" country and (B) you are not listed on any U.S. government list of prohibited or restricted parties.
  entity_types:
  - text: If you are an individual, you are at least 18 years of age or if you are less than 18 years of age, you have received the necessary consent from a parent or legal guardian to use the Services
    type: individual
  minimum_age:
    text: If you are an individual, you are at least 18 years of age or if you are less than 18 years of age, you have received the necessary consent from a parent or legal guardian to use the Services
    value: '18'
  restricted_uses:
  - summary: Lawful use only
    text: You may use the Services only for lawful purposes.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: We reserve the right, in our sole discretion, to refuse to approve a DailyPay account and to modify, delay, suspend, or terminate access to any DailyPay account and/or all or any part of the Services.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: DailyPay
provenance_date: '2026-11-09'
provider_name: DailyPay
provider_slug: dailypay
slug: dailypay-eligibility
source_date: '2026-11-09'
source_filename: dailypay-eligibility.yml
source_heading: Eligibility
source_page: https://www.dailypay.com/en-us/legal/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: DailyPay\naid: dailypay\nurl: https://www.dailypay.com/en-us/legal/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: You represent and warrant that (A) you are not located in a country that is subject to a U.S. government\n    embargo or that has been designated by the U.S. government as a \"terrorist supporting\" country and (B) you are\n    not listed on any U.S. government list of prohibited or restricted parties.\nentity_types:\n- type: individual\n  text: If you are an individual, you are at least 18 years of age or if you are less than 18\
  \ years of age, you\n    have received the necessary consent from a parent or legal guardian to use the Services\nrestricted_uses:\n- summary: Lawful use only\n  text: You may use the Services only for lawful purposes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: We reserve the right, in our sole discretion, to refuse to approve a DailyPay account and to modify, delay,\n    suspend, or terminate access to any DailyPay account and/or all or any part of the Services.\nminimum_age:\n  value: '18'\n  text: If you are an individual, you are at least 18 years of age or if you are less than 18 years of age, you\n    have received the necessary consent from a parent or legal guardian to use the Services\n"
source_yaml_url: https://artifacts.apis.io/dailypay/eligibility/dailypay-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from DailyPay's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Payments
- Payroll
- Human Resources
- Earned Wage Access
- On-Demand Pay
- Financial Services
- Fintech
- Money Transfer
- Benefits
---
