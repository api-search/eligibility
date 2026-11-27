---
api_specs:
- filename: routebase-api-specs-api-openapi.yml
  format: yaml
  label: Routebase API Specs API
  slug: routebase-api-specs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/routebase/openapi/routebase-api-specs-api-openapi.yml
- filename: routebase-ci-test-runs-api-openapi.yml
  format: yaml
  label: Routebase CI & Test Runs API
  slug: routebase-ci-test-runs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/routebase/openapi/routebase-ci-test-runs-api-openapi.yml
- filename: routebase-docs-as-code-api-openapi.yml
  format: yaml
  label: Routebase Docs as Code API
  slug: routebase-docs-as-code-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/routebase/openapi/routebase-docs-as-code-api-openapi.yml
- filename: routebase-scim-api-openapi.yml
  format: yaml
  label: Routebase SCIM API
  slug: routebase-scim-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/routebase/openapi/routebase-scim-api-openapi.yml
- filename: routebase-security-api-openapi.yml
  format: yaml
  label: Routebase Security API
  slug: routebase-security-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/routebase/openapi/routebase-security-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The service is directed exclusively at businesses, self-employed persons, and freelancers acting in the exercise of their commercial or independent professional activity
    type: business
  - text: It is not directed at, and not offered to, consumers (Verbraucher, § 13 BGB).
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Sanctioned persons or territories
    text: does not use the service for, or on behalf of, sanctioned persons or in sanctioned territories in breach of these laws.
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
name: Routebase
provenance_date: '2026-11-10'
provider_name: Routebase
provider_slug: routebase
slug: routebase-eligibility
source_date: '2026-11-10'
source_filename: routebase-eligibility.yml
source_heading: Eligibility
source_page: https://routebase.dev/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Routebase\naid: routebase\nurl: https://routebase.dev/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The service is directed exclusively at businesses, self-employed persons, and freelancers acting in the\n    exercise of their commercial or independent professional activity\n- type: individual\n  text: It is not directed at, and not offered to, consumers (Verbraucher, § 13 BGB).\nrestricted_uses:\n- summary: Sanctioned persons or territories\n  text: does not use the service for, or on behalf of, sanctioned persons or in sanctioned\
  \ territories in breach\n    of these laws.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/routebase/eligibility/routebase-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Routebase's own page on 2026-11-10.
synthetic: false
tags:
- API lifecycle management
- API Design
- OpenAPI
- API Documentation
- API Testing
- API Mocking
- API Monitoring
- API Security
- MCP
- AI Agents
- Developer Tools
- CI/CD
- REST
- OAuth 2.1
- SCIM
- Streamable HTTP
---
