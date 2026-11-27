---
api_specs:
- filename: kriya-buyers-api-openapi.yml
  format: yaml
  label: Kriya Buyers API
  slug: kriya-buyers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kriya/openapi/kriya-buyers-api-openapi.yml
- filename: kriya-onboarding-api-api-openapi.yml
  format: yaml
  label: Kriya Onboarding API
  slug: kriya-onboarding-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kriya/openapi/kriya-onboarding-api-api-openapi.yml
- filename: kriya-onboardingjourney-api-openapi.yml
  format: yaml
  label: Kriya OnboardingJourney API
  slug: kriya-onboardingjourney-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kriya/openapi/kriya-onboardingjourney-api-openapi.yml
- filename: kriya-orders-api-openapi.yml
  format: yaml
  label: Kriya Orders API
  slug: kriya-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kriya/openapi/kriya-orders-api-openapi.yml
- filename: kriya-payments-api-openapi.yml
  format: yaml
  label: Kriya Payments API
  slug: kriya-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kriya/openapi/kriya-payments-api-openapi.yml
- filename: kriya-scenario-api-openapi.yml
  format: yaml
  label: Kriya Scenario API
  slug: kriya-scenario-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kriya/openapi/kriya-scenario-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are a business user, please note that in particular, we will not be liable for loss of profits, sales, business, or revenue
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Framing and linking
    text: Our sites must not be framed on any other website, nor may you create a link to any part of our sites other than the home page.
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
name: Kriya
provenance_date: '2026-11-09'
provider_name: Kriya
provider_slug: kriya
slug: kriya-eligibility
source_date: '2026-11-09'
source_filename: kriya-eligibility.yml
source_heading: Eligibility
source_page: https://www.kriya.co/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Kriya\naid: kriya\nurl: https://www.kriya.co/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are a business user, please note that in particular, we will not be liable for loss of profits, sales,\n    business, or revenue\nrestricted_uses:\n- summary: Framing and linking\n  text: Our sites must not be framed on any other website, nor may you create a link to any part of our sites other\n    than the home page.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/kriya/eligibility/kriya-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Kriya's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Payments
- Embedded Finance
- Buy Now Pay Later
- B2B Payments
- Invoice Finance
- Lending
- Working Capital
- Onboarding
- KYC
- United Kingdom
---
