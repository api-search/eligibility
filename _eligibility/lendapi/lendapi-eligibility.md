---
api_specs:
- filename: lendapi-amortization-api-openapi.yml
  format: yaml
  label: LendAPI Amortization API
  slug: lendapi-amortization-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lendapi/openapi/lendapi-amortization-api-openapi.yml
- filename: lendapi-application-api-openapi.yml
  format: yaml
  label: LendAPI Application API
  slug: lendapi-application-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lendapi/openapi/lendapi-application-api-openapi.yml
- filename: lendapi-credit-risk-api-openapi.yml
  format: yaml
  label: LendAPI Credit Risk API
  slug: lendapi-credit-risk-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lendapi/openapi/lendapi-credit-risk-api-openapi.yml
- filename: lendapi-decision-api-openapi.yml
  format: yaml
  label: LendAPI Decision API
  slug: lendapi-decision-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lendapi/openapi/lendapi-decision-api-openapi.yml
- filename: lendapi-decisions-api-openapi.yml
  format: yaml
  label: LendAPI Decisions API
  slug: lendapi-decisions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lendapi/openapi/lendapi-decisions-api-openapi.yml
- filename: lendapi-get-app-credit-report-api-openapi.yml
  format: yaml
  label: LendAPI Get App Credit Report API
  slug: lendapi-get-app-credit-report-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lendapi/openapi/lendapi-get-app-credit-report-api-openapi.yml
- filename: lendapi-outcomes-api-openapi.yml
  format: yaml
  label: LendAPI Outcomes API
  slug: lendapi-outcomes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lendapi/openapi/lendapi-outcomes-api-openapi.yml
- filename: lendapi-page-submit-api-openapi.yml
  format: yaml
  label: LendAPI Page Submit API
  slug: lendapi-page-submit-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lendapi/openapi/lendapi-page-submit-api-openapi.yml
- filename: lendapi-pricing-engine-api-openapi.yml
  format: yaml
  label: LendAPI Pricing Engine API
  slug: lendapi-pricing-engine-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lendapi/openapi/lendapi-pricing-engine-api-openapi.yml
- filename: lendapi-pricing-engines-api-openapi.yml
  format: yaml
  label: LendAPI Pricing Engines API
  slug: lendapi-pricing-engines-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lendapi/openapi/lendapi-pricing-engines-api-openapi.yml
- filename: lendapi-sub-tenant-api-openapi.yml
  format: yaml
  label: LendAPI Sub Tenant API
  slug: lendapi-sub-tenant-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lendapi/openapi/lendapi-sub-tenant-api-openapi.yml
- filename: lendapi-sub-tenants-api-openapi.yml
  format: yaml
  label: LendAPI Sub Tenants API
  slug: lendapi-sub-tenants-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lendapi/openapi/lendapi-sub-tenants-api-openapi.yml
- filename: lendapi-variable-api-openapi.yml
  format: yaml
  label: LendAPI Variable API
  slug: lendapi-variable-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lendapi/openapi/lendapi-variable-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: the individual or organization accessing or using the LendAPI software and related services (“Client,” “you”)
    type: individual
  minimum_age:
    text: null
    value: null
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
name: LendAPI
provenance_date: '2026-11-09'
provider_name: LendAPI
provider_slug: lendapi
slug: lendapi-eligibility
source_date: '2026-11-09'
source_filename: lendapi-eligibility.yml
source_heading: Eligibility
source_page: https://www.lendapi.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: LendAPI\naid: lendapi\nurl: https://www.lendapi.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: the individual or organization accessing or using the LendAPI software and related services (“Client,” “you”)\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/lendapi/eligibility/lendapi-eligibility.yml
stated_fields:
- entity_types
summary_line: 1 quoted statement, read from LendAPI's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Lending
- Loan Origination
- Financial Services
- Fintech
- Embedded Finance
- Underwriting
- Decision Engine
- Credit
- Banking
- Account Opening
- KYC
- KYB
- Buy Now Pay Later
- Point-of-Sale
---
