---
api_specs:
- filename: secure-flows-com-ai-optional-api-openapi.yml
  format: yaml
  label: secure-flows-com AI Optional API
  slug: secure-flows-com-ai-optional-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/secure-flows-com/openapi/secure-flows-com-ai-optional-api-openapi.yml
- filename: secure-flows-com-ai-safe-api-openapi.yml
  format: yaml
  label: secure-flows-com AI Safe API
  slug: secure-flows-com-ai-safe-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/secure-flows-com/openapi/secure-flows-com-ai-safe-api-openapi.yml
- filename: secure-flows-com-applications-api-openapi.yml
  format: yaml
  label: secure-flows-com Applications API
  slug: secure-flows-com-applications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/secure-flows-com/openapi/secure-flows-com-applications-api-openapi.yml
- filename: secure-flows-com-audit-api-openapi.yml
  format: yaml
  label: secure-flows-com Audit API
  slug: secure-flows-com-audit-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/secure-flows-com/openapi/secure-flows-com-audit-api-openapi.yml
- filename: secure-flows-com-hosted-ui-api-openapi.yml
  format: yaml
  label: secure-flows-com Hosted UI API
  slug: secure-flows-com-hosted-ui-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/secure-flows-com/openapi/secure-flows-com-hosted-ui-api-openapi.yml
- filename: secure-flows-com-human-only-api-openapi.yml
  format: yaml
  label: secure-flows-com Human Only API
  slug: secure-flows-com-human-only-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/secure-flows-com/openapi/secure-flows-com-human-only-api-openapi.yml
- filename: secure-flows-com-users-api-openapi.yml
  format: yaml
  label: secure-flows-com Users API
  slug: secure-flows-com-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/secure-flows-com/openapi/secure-flows-com-users-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: you, an individual, a person, or entity, including any party or entity you legally represent
    type: individual
  - text: duly authorized to act on behalf of a legally recognized entity
    type: business
  minimum_age:
    text: you are at least eighteen (18) years of age
    value: '18'
  restricted_uses:
  - summary: Military purposes
    text: Use the Services for military purposes, including weapons development or cyber warfare
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Secure-Flows reserves the absolute and unilateral right to reject any registration request, or suspend an existing account
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: secure-flows-com
provenance_date: '2026-11-10'
provider_name: secure-flows-com
provider_slug: secure-flows-com
slug: secure-flows-com-eligibility
source_date: '2026-11-10'
source_filename: secure-flows-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.secure-flows.com/docs/legal/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: secure-flows-com\naid: secure-flows-com\nurl: https://www.secure-flows.com/docs/legal/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: you, an individual, a person, or entity, including any party or entity you legally represent\n- type: business\n  text: duly authorized to act on behalf of a legally recognized entity\nrestricted_uses:\n- summary: Military purposes\n  text: Use the Services for military purposes, including weapons development or cyber warfare\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: Secure-Flows reserves the absolute and unilateral right to reject any registration request, or suspend an\n    existing account\nminimum_age:\n  value: '18'\n  text: you are at least eighteen (18) years of age\n"
source_yaml_url: https://artifacts.apis.io/secure-flows-com/eligibility/secure-flows-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from secure-flows-com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Security
- Data-Encryption
- No-Code
- Authentication
---
