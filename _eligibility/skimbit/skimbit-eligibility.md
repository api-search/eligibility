---
api_specs:
- filename: skimbit-commissions-api-openapi.yml
  format: yaml
  label: SkimBit Commissions API
  slug: skimbit-commissions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/skimbit/openapi/skimbit-commissions-api-openapi.yml
- filename: skimbit-domains-api-openapi.yml
  format: yaml
  label: SkimBit Domains API
  slug: skimbit-domains-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/skimbit/openapi/skimbit-domains-api-openapi.yml
- filename: skimbit-merchants-api-openapi.yml
  format: yaml
  label: SkimBit Merchants API
  slug: skimbit-merchants-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/skimbit/openapi/skimbit-merchants-api-openapi.yml
- filename: skimbit-offers-api-openapi.yml
  format: yaml
  label: SkimBit Offers API
  slug: skimbit-offers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/skimbit/openapi/skimbit-offers-api-openapi.yml
- filename: skimbit-payments-api-openapi.yml
  format: yaml
  label: SkimBit Payments API
  slug: skimbit-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/skimbit/openapi/skimbit-payments-api-openapi.yml
- filename: skimbit-products-api-openapi.yml
  format: yaml
  label: SkimBit Products API
  slug: skimbit-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/skimbit/openapi/skimbit-products-api-openapi.yml
- filename: skimbit-reports-api-openapi.yml
  format: yaml
  label: SkimBit Reports API
  slug: skimbit-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/skimbit/openapi/skimbit-reports-api-openapi.yml
- filename: skimbit-verticals-api-openapi.yml
  format: yaml
  label: SkimBit Verticals API
  slug: skimbit-verticals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/skimbit/openapi/skimbit-verticals-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Governing law and forum depend on whether Publisher is located in the United States or outside it; no served or excluded countries are listed.
  entity_types:
  - text: you are a Publisher intending to enter into the Agreement with Skimlinks in a personal capacity
    type: individual
  - text: you are an employee, agent or subcontractor of a Publisher who has been given the necessary authorisations
    type: business
  minimum_age:
    text: is over 18 and cannot be an employee of Skimlinks or its affiliates
    value: '18'
  restricted_uses:
  - summary: No fraudulent or illegal activity (referral program)
    text: Publisher will not engage in any activity that may be considered fraudulent or illegal;
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Skimlinks may approve or reject an application to register for the Service at its entire discretion
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: SkimBit
provenance_date: '2026-11-10'
provider_name: SkimBit
provider_slug: skimbit
slug: skimbit-eligibility
source_date: '2026-11-10'
source_filename: skimbit-eligibility.yml
source_heading: Eligibility
source_page: https://www.skimlinks.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: SkimBit\naid: skimbit\nurl: https://www.skimlinks.com/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Governing law and forum depend on whether Publisher is located in the United States or outside it; no served\n    or excluded countries are listed.\nentity_types:\n- type: individual\n  text: you are a Publisher intending to enter into the Agreement with Skimlinks in a personal capacity\n- type: business\n  text: you are an employee, agent or subcontractor of a Publisher who has been given the necessary authorisations\nrestricted_uses:\n- summary: No fraudulent\
  \ or illegal activity (referral program)\n  text: Publisher will not engage in any activity that may be considered fraudulent or illegal;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Skimlinks may approve or reject an application to register for the Service at its entire discretion\nminimum_age:\n  value: '18'\n  text: is over 18 and cannot be an employee of Skimlinks or its affiliates\n"
source_yaml_url: https://artifacts.apis.io/skimbit/eligibility/skimbit-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from SkimBit's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Affiliate Marketing
- Content Monetization
- Commerce
- Publishers
- Advertising
- Retail
- Reporting
- Product
- E-Commerce
---
