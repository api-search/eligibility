---
api_specs:
- filename: synchrony-financial-applications-api-openapi.yml
  format: yaml
  label: Synchrony Financial Applications API
  slug: synchrony-financial-applications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/synchrony-financial/openapi/synchrony-financial-applications-api-openapi.yml
- filename: synchrony-financial-decisions-api-openapi.yml
  format: yaml
  label: Synchrony Financial Decisions API
  slug: synchrony-financial-decisions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/synchrony-financial/openapi/synchrony-financial-decisions-api-openapi.yml
- filename: synchrony-financial-payments-api-openapi.yml
  format: yaml
  label: Synchrony Financial Payments API
  slug: synchrony-financial-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/synchrony-financial/openapi/synchrony-financial-payments-api-openapi.yml
- filename: synchrony-financial-preapprovals-api-openapi.yml
  format: yaml
  label: Synchrony Financial Preapprovals API
  slug: synchrony-financial-preapprovals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/synchrony-financial/openapi/synchrony-financial-preapprovals-api-openapi.yml
- filename: synchrony-financial-preauthorizations-api-openapi.yml
  format: yaml
  label: Synchrony Financial Preauthorizations API
  slug: synchrony-financial-preauthorizations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/synchrony-financial/openapi/synchrony-financial-preauthorizations-api-openapi.yml
- filename: synchrony-financial-purchases-api-openapi.yml
  format: yaml
  label: Synchrony Financial Purchases API
  slug: synchrony-financial-purchases-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/synchrony-financial/openapi/synchrony-financial-purchases-api-openapi.yml
- filename: synchrony-financial-refunds-api-openapi.yml
  format: yaml
  label: Synchrony Financial Refunds API
  slug: synchrony-financial-refunds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/synchrony-financial/openapi/synchrony-financial-refunds-api-openapi.yml
- filename: synchrony-financial-reversals-api-openapi.yml
  format: yaml
  label: Synchrony Financial Reversals API
  slug: synchrony-financial-reversals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/synchrony-financial/openapi/synchrony-financial-reversals-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are an individual working for a company, then the term “Developer” includes you and your company
    type: business
  - text: the person registering for the Developer Portal and/or accessing or using the Materials
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No production use without approval
    text: Use the Materials or Platforms for production purposes unless and until Synchrony provides its approval in accordance with Section 4.4
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Synchrony may require Developer to verify its identity.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Synchrony Financial
provenance_date: '2026-11-10'
provider_name: Synchrony Financial
provider_slug: synchrony-financial
slug: synchrony-financial-eligibility
source_date: '2026-11-10'
source_filename: synchrony-financial-eligibility.yml
source_heading: Eligibility
source_page: https://developer.syf.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Synchrony Financial\naid: synchrony-financial\nurl: https://developer.syf.com/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are an individual working for a company, then the term “Developer” includes you and your company\n- type: individual\n  text: the person registering for the Developer Portal and/or accessing or using the Materials\nrestricted_uses:\n- summary: No production use without approval\n  text: Use the Materials or Platforms for production purposes unless and until Synchrony provides its approval\n\
  \    in accordance with Section 4.4\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Synchrony may require Developer to verify its identity.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/synchrony-financial/eligibility/synchrony-financial-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from Synchrony Financial's own page on 2026-11-10.
synthetic: false
tags:
- Financial Services
- Credit
- Payments
- Consumer Finance
- Retail Finance
---
