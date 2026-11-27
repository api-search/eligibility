---
api_specs:
- filename: solo-io-api-keys-api-openapi.yml
  format: yaml
  label: Solo.io API Keys API
  slug: solo-io-api-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/solo-io/openapi/solo-io-api-keys-api-openapi.yml
- filename: solo-io-api-products-api-openapi.yml
  format: yaml
  label: Solo.io API Products API
  slug: solo-io-api-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/solo-io/openapi/solo-io-api-products-api-openapi.yml
- filename: solo-io-applications-api-openapi.yml
  format: yaml
  label: Solo.io Applications API
  slug: solo-io-applications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/solo-io/openapi/solo-io-applications-api-openapi.yml
- filename: solo-io-apps-api-openapi.yml
  format: yaml
  label: Solo.io Apps API
  slug: solo-io-apps-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/solo-io/openapi/solo-io-apps-api-openapi.yml
- filename: solo-io-auth-api-openapi.yml
  format: yaml
  label: Solo.io Auth API
  slug: solo-io-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/solo-io/openapi/solo-io-auth-api-openapi.yml
- filename: solo-io-health-api-openapi.yml
  format: yaml
  label: Solo.io Health API
  slug: solo-io-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/solo-io/openapi/solo-io-health-api-openapi.yml
- filename: solo-io-me-api-openapi.yml
  format: yaml
  label: Solo.io Me API
  slug: solo-io-me-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/solo-io/openapi/solo-io-me-api-openapi.yml
- filename: solo-io-metadata-api-openapi.yml
  format: yaml
  label: Solo.io Metadata API
  slug: solo-io-metadata-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/solo-io/openapi/solo-io-metadata-api-openapi.yml
- filename: solo-io-oauth-credentials-api-openapi.yml
  format: yaml
  label: Solo.io OAUTH Credentials API
  slug: solo-io-oauth-credentials-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/solo-io/openapi/solo-io-oauth-credentials-api-openapi.yml
- filename: solo-io-subscriptions-api-openapi.yml
  format: yaml
  label: Solo.io Subscriptions API
  slug: solo-io-subscriptions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/solo-io/openapi/solo-io-subscriptions-api-openapi.yml
- filename: solo-io-teams-api-openapi.yml
  format: yaml
  label: Solo.io Teams API
  slug: solo-io-teams-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/solo-io/openapi/solo-io-teams-api-openapi.yml
- filename: solo-io-user-api-openapi.yml
  format: yaml
  label: Solo.io User API
  slug: solo-io-user-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/solo-io/openapi/solo-io-user-api-openapi.yml
- filename: solo-io-users-api-openapi.yml
  format: yaml
  label: Solo.io Users API
  slug: solo-io-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/solo-io/openapi/solo-io-users-api-openapi.yml
- filename: solo-io-webhooks-api-openapi.yml
  format: yaml
  label: Solo.io Webhooks API
  slug: solo-io-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/solo-io/openapi/solo-io-webhooks-api-openapi.yml
- filename: solo-io-apis-api-openapi.yml
  format: yaml
  label: Solo.io APIs API
  slug: solo-io-apis-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/solo-io/openapi/solo-io-apis-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: you are not located in, under the control of, or a national or resident of, any country to which the United States has embargoed goods
  entity_types:
  - text: This Website is intended for business users who are at least 18 years old.
    type: business
  minimum_age:
    text: This Website is intended for business users who are at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: Illegal or unauthorized purpose
    text: (6) you will not use the Website for any illegal or unauthorized purpose
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
name: Solo.io
provenance_date: '2026-11-10'
provider_name: Solo.io
provider_slug: solo-io
slug: solo-io-eligibility
source_date: '2026-11-10'
source_filename: solo-io-eligibility.yml
source_heading: Eligibility
source_page: https://legal.solo.io/#website-terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Solo.io\naid: solo-io\nurl: https://legal.solo.io/#website-terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: you are not located in, under the control of, or a national or resident of, any country to which the United\n    States has embargoed goods\nentity_types:\n- type: business\n  text: This Website is intended for business users who are at least 18 years old.\nrestricted_uses:\n- summary: Illegal or unauthorized purpose\n  text: (6) you will not use the Website for any illegal or unauthorized purpose\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n\
  \  text: null\nminimum_age:\n  value: '18'\n  text: This Website is intended for business users who are at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/solo-io/eligibility/solo-io-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Solo.io's own page on 2026-11-10.
synthetic: false
tags:
- Company
- API Gateway
- Service Mesh
- Kubernetes
- Istio
- Envoy
- AI Gateway
- AI Agents
- MCP
- Developer Portal
- Cloud-Native
- Open Source
---
