---
api_specs:
- filename: payflex-authentication-api-openapi.yml
  format: yaml
  label: Payflex Authentication API
  slug: payflex-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/payflex/openapi/payflex-authentication-api-openapi.yml
- filename: payflex-configuration-api-openapi.yml
  format: yaml
  label: Payflex Configuration API
  slug: payflex-configuration-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/payflex/openapi/payflex-configuration-api-openapi.yml
- filename: payflex-orders-api-openapi.yml
  format: yaml
  label: Payflex Orders API
  slug: payflex-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/payflex/openapi/payflex-orders-api-openapi.yml
- filename: payflex-refunds-api-openapi.yml
  format: yaml
  label: Payflex Refunds API
  slug: payflex-refunds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/payflex/openapi/payflex-refunds-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - ZA
    text: 'You confirm that you: 5.1.4.1. are a permanent resident of South Africa'
  entity_types:
  - text: “Customer”/”you”/”your” means the person who makes use of the Payflex Platform to purchase Goods from a Retailer;
    type: individual
  minimum_age:
    text: are over 18 years of age;
    value: '18'
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: We do not guarantee acceptance to the Pay-Later Service and reserve the right to decline your request for the Pay-Later Service at our sole discretion
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Payflex
provenance_date: '2026-11-10'
provider_name: Payflex
provider_slug: payflex
slug: payflex-eligibility
source_date: '2026-11-10'
source_filename: payflex-eligibility.yml
source_heading: Eligibility
source_page: https://payflex.co.za/terms-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Payflex\naid: payflex\nurl: https://payflex.co.za/terms-conditions/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - ZA\n  excluded: []\n  text: 'You confirm that you: 5.1.4.1. are a permanent resident of South Africa'\nentity_types:\n- type: individual\n  text: “Customer”/”you”/”your” means the person who makes use of the Payflex Platform to purchase Goods from a\n    Retailer;\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: We do not guarantee acceptance to the Pay-Later Service and reserve the right to decline your request for\n    the Pay-Later Service\
  \ at our sole discretion\nminimum_age:\n  value: '18'\n  text: are over 18 years of age;\n"
source_yaml_url: https://artifacts.apis.io/payflex/eligibility/payflex-eligibility.yml
stated_fields:
- countries
- entity_types
- verification
- minimum_age
summary_line: 4 quoted statements, read from Payflex's own page on 2026-11-10.
synthetic: false
tags:
- Buy Now Pay Later
- Payments
- Installments
- South Africa
- Fintech
- E-Commerce
---
