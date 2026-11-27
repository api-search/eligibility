---
api_specs:
- filename: cerbos-admin-audit-api-openapi.yml
  format: yaml
  label: Cerbos Admin Audit API
  slug: cerbos-admin-audit-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cerbos/openapi/cerbos-admin-audit-api-openapi.yml
- filename: cerbos-admin-policies-api-openapi.yml
  format: yaml
  label: Cerbos Admin Policies API
  slug: cerbos-admin-policies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cerbos/openapi/cerbos-admin-policies-api-openapi.yml
- filename: cerbos-admin-schemas-api-openapi.yml
  format: yaml
  label: Cerbos Admin Schemas API
  slug: cerbos-admin-schemas-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cerbos/openapi/cerbos-admin-schemas-api-openapi.yml
- filename: cerbos-admin-store-api-openapi.yml
  format: yaml
  label: Cerbos Admin Store API
  slug: cerbos-admin-store-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cerbos/openapi/cerbos-admin-store-api-openapi.yml
- filename: cerbos-check-api-openapi.yml
  format: yaml
  label: Cerbos Check API
  slug: cerbos-check-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cerbos/openapi/cerbos-check-api-openapi.yml
- filename: cerbos-plan-api-openapi.yml
  format: yaml
  label: Cerbos Plan API
  slug: cerbos-plan-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cerbos/openapi/cerbos-plan-api-openapi.yml
- filename: cerbos-server-api-openapi.yml
  format: yaml
  label: Cerbos Server API
  slug: cerbos-server-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cerbos/openapi/cerbos-server-api-openapi.yml
- filename: cerbos-auth-zen-api-openapi.yml
  format: yaml
  label: Cerbos Auth ZEN API
  slug: cerbos-auth-zen-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cerbos/openapi/cerbos-auth-zen-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Company grants you a non-transferable, non-exclusive, revocable, limited licence to use and access the Site solely for your own personal, non-commercial use.
    type: individual
  - text: you are accepting these Terms (on behalf of yourself or the entity that you represent)
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Acceptable Use Policy for User Content
    text: You agree not to use the Site to collect, upload, transmit, display, or distribute any User Content
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
name: Cerbos
provenance_date: '2026-11-09'
provider_name: Cerbos
provider_slug: cerbos
slug: cerbos-eligibility
source_date: '2026-11-09'
source_filename: cerbos-eligibility.yml
source_heading: Eligibility
source_page: https://www.cerbos.dev/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cerbos\naid: cerbos\nurl: https://www.cerbos.dev/tos\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Company grants you a non-transferable, non-exclusive, revocable, limited licence to use and access the Site\n    solely for your own personal, non-commercial use.\n- type: business\n  text: you are accepting these Terms (on behalf of yourself or the entity that you represent)\nrestricted_uses:\n- summary: Acceptable Use Policy for User Content\n  text: You agree not to use the Site to collect, upload, transmit, display, or distribute\
  \ any User Content\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/cerbos/eligibility/cerbos-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Cerbos's own page on 2026-11-09.
synthetic: false
tags:
- ABAC
- Access Control
- Authorization
- AuthZEN
- Open Source
- PBAC
- PDP
- Permissions
- Policy as Code
- RBAC
- ReBAC
- Zero Trust
---
