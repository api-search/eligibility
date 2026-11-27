---
api_specs:
- filename: trend-ai-api-openapi.yml
  format: yaml
  label: Trend AI API
  slug: trend-ai-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trend/openapi/trend-ai-api-openapi.yml
- filename: trend-auth-api-openapi.yml
  format: yaml
  label: Trend Auth API
  slug: trend-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trend/openapi/trend-auth-api-openapi.yml
- filename: trend-basic-authentication-ai-api-openapi.yml
  format: yaml
  label: Trend Basic Authentication (AI) API
  slug: trend-basic-authentication-ai-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trend/openapi/trend-basic-authentication-ai-api-openapi.yml
- filename: trend-brand-admin-api-openapi.yml
  format: yaml
  label: Trend Brand Admin API
  slug: trend-brand-admin-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trend/openapi/trend-brand-admin-api-openapi.yml
- filename: trend-brand-api-openapi.yml
  format: yaml
  label: Trend Brand API
  slug: trend-brand-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trend/openapi/trend-brand-api-openapi.yml
- filename: trend-brand-authentication-api-openapi.yml
  format: yaml
  label: Trend Brand Authentication API
  slug: trend-brand-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trend/openapi/trend-brand-authentication-api-openapi.yml
- filename: trend-campaign-api-openapi.yml
  format: yaml
  label: Trend Campaign API
  slug: trend-campaign-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trend/openapi/trend-campaign-api-openapi.yml
- filename: trend-content-api-openapi.yml
  format: yaml
  label: Trend Content API
  slug: trend-content-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trend/openapi/trend-content-api-openapi.yml
- filename: trend-creator-api-openapi.yml
  format: yaml
  label: Trend Creator API
  slug: trend-creator-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trend/openapi/trend-creator-api-openapi.yml
- filename: trend-creator-authentication-api-openapi.yml
  format: yaml
  label: Trend Creator Authentication API
  slug: trend-creator-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trend/openapi/trend-creator-authentication-api-openapi.yml
- filename: trend-creator-portfolio-api-openapi.yml
  format: yaml
  label: Trend Creator Portfolio API
  slug: trend-creator-portfolio-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trend/openapi/trend-creator-portfolio-api-openapi.yml
- filename: trend-creator-profiles-api-openapi.yml
  format: yaml
  label: Trend Creator Profiles API
  slug: trend-creator-profiles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trend/openapi/trend-creator-profiles-api-openapi.yml
- filename: trend-health-check-api-openapi.yml
  format: yaml
  label: Trend Health Check API
  slug: trend-health-check-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trend/openapi/trend-health-check-api-openapi.yml
- filename: trend-message-api-openapi.yml
  format: yaml
  label: Trend Message API
  slug: trend-message-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trend/openapi/trend-message-api-openapi.yml
- filename: trend-metrics-api-openapi.yml
  format: yaml
  label: Trend Metrics API
  slug: trend-metrics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trend/openapi/trend-metrics-api-openapi.yml
- filename: trend-partnership-api-openapi.yml
  format: yaml
  label: Trend Partnership API
  slug: trend-partnership-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trend/openapi/trend-partnership-api-openapi.yml
- filename: trend-payment-api-openapi.yml
  format: yaml
  label: Trend Payment API
  slug: trend-payment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trend/openapi/trend-payment-api-openapi.yml
- filename: trend-review-api-openapi.yml
  format: yaml
  label: Trend Review API
  slug: trend-review-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trend/openapi/trend-review-api-openapi.yml
- filename: trend-shipment-api-openapi.yml
  format: yaml
  label: Trend Shipment API
  slug: trend-shipment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trend/openapi/trend-shipment-api-openapi.yml
- filename: trend-upload-api-openapi.yml
  format: yaml
  label: Trend Upload API
  slug: trend-upload-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trend/openapi/trend-upload-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: We do not represent that the Services are appropriate or available for use in other locations outside of the United States.
  entity_types:
  - text: To register an Account with soona, you must be 18 years or over.
    type: individual
  - text: if you represent an entity or other organization, that entity or organization (in either case “ you ” or “ your ”)
    type: business
  minimum_age:
    text: To register an Account with soona, you must be 18 years or over.
    value: '18'
  restricted_uses:
  - summary: Automated account creation
    text: create user accounts by automated means or under fraudulent or false pretenses
  - summary: Violating law
    text: violate any applicable federal, state, local or international law or regulation
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
name: Trend
provenance_date: '2026-11-10'
provider_name: Trend
provider_slug: trend
slug: trend-eligibility
source_date: '2026-11-10'
source_filename: trend-eligibility.yml
source_heading: Eligibility
source_page: https://soona.co/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Trend\naid: trend\nurl: https://soona.co/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: We do not represent that the Services are appropriate or available for use in other locations outside of\n    the United States.\nentity_types:\n- type: individual\n  text: To register an Account with soona, you must be 18 years or over.\n- type: business\n  text: if you represent an entity or other organization, that entity or organization (in either case “ you ” or\n    “ your ”)\nrestricted_uses:\n- summary: Automated account creation\n  text: create user accounts by automated means\
  \ or under fraudulent or false pretenses\n- summary: Violating law\n  text: violate any applicable federal, state, local or international law or regulation\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: To register an Account with soona, you must be 18 years or over.\n"
source_yaml_url: https://artifacts.apis.io/trend/eligibility/trend-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from Trend's own page on 2026-11-10.
synthetic: false
tags:
- Company
- User Generated Content
- Creator Economy
- Content Marketing
- Video Production
- Photography
- Marketing
- E-Commerce
- Creator Marketplace
- Influencer Marketing
- AI Image Generation
- Payments
---
