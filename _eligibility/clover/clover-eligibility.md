---
api_specs:
- filename: clover-charges-api-openapi.yml
  format: yaml
  label: Clover CHARGES API
  slug: clover-charges-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clover/openapi/clover-charges-api-openapi.yml
- filename: clover-checkout-api-openapi.yml
  format: yaml
  label: Clover CHECKOUT API
  slug: clover-checkout-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clover/openapi/clover-checkout-api-openapi.yml
- filename: clover-customers-api-openapi.yml
  format: yaml
  label: Clover CUSTOMERS API
  slug: clover-customers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clover/openapi/clover-customers-api-openapi.yml
- filename: clover-employees-api-openapi.yml
  format: yaml
  label: Clover EMPLOYEES API
  slug: clover-employees-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clover/openapi/clover-employees-api-openapi.yml
- filename: clover-inventory-api-openapi.yml
  format: yaml
  label: Clover INVENTORY API
  slug: clover-inventory-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clover/openapi/clover-inventory-api-openapi.yml
- filename: clover-orders-api-openapi.yml
  format: yaml
  label: Clover ORDERS API
  slug: clover-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clover/openapi/clover-orders-api-openapi.yml
- filename: clover-payments-api-openapi.yml
  format: yaml
  label: Clover PAYMENTS API
  slug: clover-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clover/openapi/clover-payments-api-openapi.yml
- filename: clover-refunds-api-openapi.yml
  format: yaml
  label: Clover REFUNDS API
  slug: clover-refunds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clover/openapi/clover-refunds-api-openapi.yml
- filename: clover-tokens-api-openapi.yml
  format: yaml
  label: Clover TOKENS API
  slug: clover-tokens-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clover/openapi/clover-tokens-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: References in these Terms to Clover means Clover Network, LLC where the relevant Location is the United States of America, and the applicable affiliate of Clover Network, LLC where the relevant Location is outside of the United States of America.
  entity_types:
  - text: You shall provide Clover with honest, accurate, current, and complete information about you and your business
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Alcohol orders must be for customers 21+
    text: Where the Location is the United States of America, you must ensure that any customer who places an order for an alcoholic beverage is 21 years of age or older.
  - summary: No protected health information
    text: upload or incorporate, process transactions involving, or otherwise provide Clover with, any information considered “protected health information” within the meaning of the US Health Insurance Portability and Accountability Act of 1996, as amended (HIPAA)
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Clover accounts are subject to approval, including credit approval.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Clover
provenance_date: '2026-11-09'
provider_name: Clover
provider_slug: clover
slug: clover-eligibility
source_date: '2026-11-09'
source_filename: clover-eligibility.yml
source_heading: Eligibility
source_page: https://www.clover.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Clover\naid: clover\nurl: https://www.clover.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: References in these Terms to Clover means Clover Network, LLC where the relevant Location is the United\n    States of America, and the applicable affiliate of Clover Network, LLC where the relevant Location is outside\n    of the United States of America.\nentity_types:\n- type: business\n  text: You shall provide Clover with honest, accurate, current, and complete information about you and your business\nrestricted_uses:\n- summary: Alcohol orders must be for customers 21+\n \
  \ text: Where the Location is the United States of America, you must ensure that any customer who places an order\n    for an alcoholic beverage is 21 years of age or older.\n- summary: No protected health information\n  text: upload or incorporate, process transactions involving, or otherwise provide Clover with, any information\n    considered “protected health information” within the meaning of the US Health Insurance Portability and Accountability\n    Act of 1996, as amended (HIPAA)\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Clover accounts are subject to approval, including credit approval.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/clover/eligibility/clover-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 5 quoted statements, read from Clover's own page on 2026-11-09.
synthetic: false
tags:
- Restaurant
- Point-of-Sale
- Payments
- Retail
- Small Business
- Hardware
---
