---
api_specs:
- filename: even-financial-analytics-api-openapi.yml
  format: yaml
  label: Even Financial Analytics API
  slug: even-financial-analytics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/even-financial/openapi/even-financial-analytics-api-openapi.yml
- filename: even-financial-approval-probability-api-openapi.yml
  format: yaml
  label: Even Financial Approval Probability API
  slug: even-financial-approval-probability-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/even-financial/openapi/even-financial-approval-probability-api-openapi.yml
- filename: even-financial-lead-api-openapi.yml
  format: yaml
  label: Even Financial Lead API
  slug: even-financial-lead-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/even-financial/openapi/even-financial-lead-api-openapi.yml
- filename: even-financial-offer-preview-api-openapi.yml
  format: yaml
  label: Even Financial Offer Preview API
  slug: even-financial-offer-preview-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/even-financial/openapi/even-financial-offer-preview-api-openapi.yml
- filename: even-financial-ui-utils-api-openapi.yml
  format: yaml
  label: Even Financial UI Utils API
  slug: even-financial-ui-utils-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/even-financial/openapi/even-financial-ui-utils-api-openapi.yml
- filename: even-financial-pre-fill-api-openapi.yml
  format: yaml
  label: Even Financial Pre Fill API
  slug: even-financial-pre-fill-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/even-financial/openapi/even-financial-pre-fill-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are under 18 years of age, you are not authorized to use the Services, with or without registering.
    type: individual
  minimum_age:
    text: If you are under 18 years of age, you are not authorized to use the Services, with or without registering.
    value: '18'
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
name: Even Financial
provenance_date: '2026-11-09'
provider_name: Even Financial
provider_slug: even-financial
slug: even-financial-eligibility
source_date: '2026-11-09'
source_filename: even-financial-eligibility.yml
source_heading: Eligibility
source_page: https://engine.tech/resources/legal#terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Even Financial\naid: even-financial\nurl: https://engine.tech/resources/legal#terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: If you are under 18 years of age, you are not authorized to use the Services, with or without registering.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: If you are under 18 years of age, you are not authorized to use the Services, with or without registering.\n"
source_yaml_url: https://artifacts.apis.io/even-financial/eligibility/even-financial-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from Even Financial's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Financial Services
- Embedded Finance
- Fintech
- Lending
- Personal Loans
- Credit Cards
- Marketplace
- Recommendation Engine
- Lead Generation
---
