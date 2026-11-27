---
api_specs:
- filename: gloo-api-products-api-openapi.yml
  format: yaml
  label: Gloo API Products API
  slug: gloo-api-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gloo/openapi/gloo-api-products-api-openapi.yml
- filename: gloo-applications-api-openapi.yml
  format: yaml
  label: Gloo Applications API
  slug: gloo-applications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gloo/openapi/gloo-applications-api-openapi.yml
- filename: gloo-me-api-openapi.yml
  format: yaml
  label: Gloo Me API
  slug: gloo-me-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gloo/openapi/gloo-me-api-openapi.yml
- filename: gloo-subscriptions-api-openapi.yml
  format: yaml
  label: Gloo Subscriptions API
  slug: gloo-subscriptions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gloo/openapi/gloo-subscriptions-api-openapi.yml
- filename: gloo-teams-api-openapi.yml
  format: yaml
  label: Gloo Teams API
  slug: gloo-teams-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gloo/openapi/gloo-teams-api-openapi.yml
- filename: gloo-user-api-openapi.yml
  format: yaml
  label: Gloo User API
  slug: gloo-user-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gloo/openapi/gloo-user-api-openapi.yml
- filename: gloo-webhooks-api-openapi.yml
  format: yaml
  label: Gloo Webhooks API
  slug: gloo-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gloo/openapi/gloo-webhooks-api-openapi.yml
- filename: gloo-apis-api-openapi.yml
  format: yaml
  label: Gloo APIs API
  slug: gloo-apis-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gloo/openapi/gloo-apis-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: This Website is intended for business users who are at least 18 years old.
    type: business
  - text: If you are a parent or legal guardian who is registering for a child, you hereby agree to bind your child to the Terms of Use
    type: individual
  minimum_age:
    text: This Website is intended for business users who are at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: No competitive advertising
    text: (i) any advertisement, promotional materials or solicitation related to any product or service that is competitive with Solo products or services
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
name: Gloo
provenance_date: '2026-11-09'
provider_name: Gloo
provider_slug: gloo
slug: gloo-eligibility
source_date: '2026-11-09'
source_filename: gloo-eligibility.yml
source_heading: Eligibility
source_page: https://legal.solo.io/#website-terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Gloo\naid: gloo\nurl: https://legal.solo.io/#website-terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: This Website is intended for business users who are at least 18 years old.\n- type: individual\n  text: If you are a parent or legal guardian who is registering for a child, you hereby agree to bind your child\n    to the Terms of Use\nrestricted_uses:\n- summary: No competitive advertising\n  text: (i) any advertisement, promotional materials or solicitation related to any product or service that is competitive\n    with\
  \ Solo products or services\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: This Website is intended for business users who are at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/gloo/eligibility/gloo-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Gloo's own page on 2026-11-09.
synthetic: false
tags:
- API Gateway
- Cloud-Native
- Developer Portal
- Envoy
- Istio
- Kubernetes
- Kubernetes Gateway API
- Open Source
- Service Mesh
---
