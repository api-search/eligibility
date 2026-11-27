---
api_specs:
- filename: auditae-app-billing-api-openapi.yml
  format: yaml
  label: AuditAE Billing API
  slug: auditae-app-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/auditae-app/openapi/auditae-app-billing-api-openapi.yml
- filename: auditae-app-citations-api-openapi.yml
  format: yaml
  label: AuditAE Citations API
  slug: auditae-app-citations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/auditae-app/openapi/auditae-app-citations-api-openapi.yml
- filename: auditae-app-schema-api-openapi.yml
  format: yaml
  label: AuditAE Schema API
  slug: auditae-app-schema-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/auditae-app/openapi/auditae-app-schema-api-openapi.yml
- filename: auditae-app-technical-api-openapi.yml
  format: yaml
  label: AuditAE Technical API
  slug: auditae-app-technical-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/auditae-app/openapi/auditae-app-technical-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Service is intended for business and professional use.
    type: business
  minimum_age:
    text: You must be at least 18 years old and able to form a binding contract.
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
name: AuditAE
provenance_date: '2026-11-09'
provider_name: AuditAE
provider_slug: auditae-app
slug: auditae-app-eligibility
source_date: '2026-11-09'
source_filename: auditae-app-eligibility.yml
source_heading: Eligibility
source_page: https://auditae.app/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AuditAE\naid: auditae-app\nurl: https://auditae.app/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The Service is intended for business and professional use.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and able to form a binding contract.\n"
source_yaml_url: https://artifacts.apis.io/auditae-app/eligibility/auditae-app-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from AuditAE's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- SEO
- Marketing
- Software-as-a-Service
- Visibility
---
