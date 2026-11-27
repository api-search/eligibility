---
api_specs:
- filename: riskified-automation-endpoints-api-openapi.yml
  format: yaml
  label: Riskified Automation Endpoints API
  slug: riskified-automation-endpoints-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/riskified/openapi/riskified-automation-endpoints-api-openapi.yml
- filename: riskified-customer-actions-api-openapi.yml
  format: yaml
  label: Riskified Customer Actions API
  slug: riskified-customer-actions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/riskified/openapi/riskified-customer-actions-api-openapi.yml
- filename: riskified-customer-management-api-openapi.yml
  format: yaml
  label: Riskified Customer Management API
  slug: riskified-customer-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/riskified/openapi/riskified-customer-management-api-openapi.yml
- filename: riskified-order-pre-auth-review-and-psd2-3ds-cvv-recommendations-api-openapi.yml
  format: yaml
  label: Riskified Order Pre-Auth Review and PSD2/3DS/CVV Recommendations API
  slug: riskified-order-pre-auth-review-and-psd2-3ds-cvv-recommendations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/riskified/openapi/riskified-order-pre-auth-review-and-psd2-3ds-cvv-recommendations-api-openapi.yml
- filename: riskified-otp-recover-sync-flow-api-openapi.yml
  format: yaml
  label: Riskified OTP Recover (Sync flow) API
  slug: riskified-otp-recover-sync-flow-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/riskified/openapi/riskified-otp-recover-sync-flow-api-openapi.yml
- filename: riskified-post-authorization-flow-api-openapi.yml
  format: yaml
  label: Riskified Post-Authorization Flow API
  slug: riskified-post-authorization-flow-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/riskified/openapi/riskified-post-authorization-flow-api-openapi.yml
- filename: riskified-pre-authorization-flow-api-openapi.yml
  format: yaml
  label: Riskified Pre-Authorization Flow API
  slug: riskified-pre-authorization-flow-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/riskified/openapi/riskified-pre-authorization-flow-api-openapi.yml
- filename: riskified-refunds-api-openapi.yml
  format: yaml
  label: Riskified Refunds API
  slug: riskified-refunds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/riskified/openapi/riskified-refunds-api-openapi.yml
- filename: riskified-returns-api-openapi.yml
  format: yaml
  label: Riskified Returns API
  slug: riskified-returns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/riskified/openapi/riskified-returns-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: If Client is domiciled in North America, Central America, or South America, Client is entering into the Agreement with Riskified, Inc., a Delaware corporation.
  entity_types:
  - text: by and between the entity named below and each of its Affiliates entering into an Order Form (“ Client ”)
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No consumer eligibility determinations (FCRA)
    text: Client represents and warrants that it shall not use the Services to determine any consumer’s eligibility for any product or service to be used by a consumer for personal, family or household purposes.
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
name: Riskified
provenance_date: '2026-11-10'
provider_name: Riskified
provider_slug: riskified
slug: riskified-eligibility
source_date: '2026-11-10'
source_filename: riskified-eligibility.yml
source_heading: Eligibility
source_page: https://www.riskified.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Riskified\naid: riskified\nurl: https://www.riskified.com/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: If Client is domiciled in North America, Central America, or South America, Client is entering into the\n    Agreement with Riskified, Inc., a Delaware corporation.\nentity_types:\n- type: business\n  text: by and between the entity named below and each of its Affiliates entering into an Order Form (“ Client ”)\nrestricted_uses:\n- summary: No consumer eligibility determinations (FCRA)\n  text: Client represents and warrants that it shall not use the\
  \ Services to determine any consumer’s eligibility\n    for any product or service to be used by a consumer for personal, family or household purposes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/riskified/eligibility/riskified-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Riskified's own page on 2026-11-10.
synthetic: false
tags:
- Fraud Prevention
- Chargebacks
- E-Commerce
- Payments
- Risk Management
- Machine Learning
- Account Takeover
- Policy Abuse
- 3D
- PSD2
- Returns
---
