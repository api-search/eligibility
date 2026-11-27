---
api_specs:
- filename: diligent-cdd-api-openapi.yml
  format: yaml
  label: Diligent CDD API
  slug: diligent-cdd-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/diligent/openapi/diligent-cdd-api-openapi.yml
- filename: diligent-company-api-openapi.yml
  format: yaml
  label: Diligent Company API
  slug: diligent-company-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/diligent/openapi/diligent-company-api-openapi.yml
- filename: diligent-instant-screening-experimental-api-openapi.yml
  format: yaml
  label: Diligent Instant Screening (experimental) API
  slug: diligent-instant-screening-experimental-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/diligent/openapi/diligent-instant-screening-experimental-api-openapi.yml
- filename: diligent-monitorings-api-openapi.yml
  format: yaml
  label: Diligent Monitorings API
  slug: diligent-monitorings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/diligent/openapi/diligent-monitorings-api-openapi.yml
- filename: diligent-name-screening-api-openapi.yml
  format: yaml
  label: Diligent Name Screening API
  slug: diligent-name-screening-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/diligent/openapi/diligent-name-screening-api-openapi.yml
- filename: diligent-webhooks-api-openapi.yml
  format: yaml
  label: Diligent Webhooks API
  slug: diligent-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/diligent/openapi/diligent-webhooks-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You must be at least 18 years old and legally capable of entering into a contract to use the Services.
    value: '18'
  restricted_uses:
  - summary: Violating data protection or industry regulations
    text: Use the Services in a way that violates data protection or industry regulations.
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
name: Diligent
provenance_date: '2026-11-09'
provider_name: Diligent
provider_slug: diligent
slug: diligent-eligibility
source_date: '2026-11-09'
source_filename: diligent-eligibility.yml
source_heading: Eligibility
source_page: https://www.godiligent.ai/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Diligent\naid: diligent\nurl: https://www.godiligent.ai/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Violating data protection or industry regulations\n  text: Use the Services in a way that violates data protection or industry regulations.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and legally capable of entering into a contract to use the Services.\n"
source_yaml_url: https://artifacts.apis.io/diligent/eligibility/diligent-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Diligent's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Compliance
- RegTech
- KYC
- AML
- Financial Crime
- Due Diligence
- Screening
- Sanctions
- Monitoring
- Artificial Intelligence
- Fintech
- Webhook
---
