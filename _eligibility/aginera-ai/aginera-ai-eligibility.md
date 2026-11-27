---
api_specs:
- filename: aginera-ai-billing-api-openapi.yml
  format: yaml
  label: Aginera Billing API
  slug: aginera-ai-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aginera-ai/openapi/aginera-ai-billing-api-openapi.yml
- filename: aginera-ai-cad-api-openapi.yml
  format: yaml
  label: Aginera CAD API
  slug: aginera-ai-cad-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aginera-ai/openapi/aginera-ai-cad-api-openapi.yml
- filename: aginera-ai-clients-api-openapi.yml
  format: yaml
  label: Aginera Clients API
  slug: aginera-ai-clients-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aginera-ai/openapi/aginera-ai-clients-api-openapi.yml
- filename: aginera-ai-documents-api-openapi.yml
  format: yaml
  label: Aginera Documents API
  slug: aginera-ai-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aginera-ai/openapi/aginera-ai-documents-api-openapi.yml
- filename: aginera-ai-exports-api-openapi.yml
  format: yaml
  label: Aginera Exports API
  slug: aginera-ai-exports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aginera-ai/openapi/aginera-ai-exports-api-openapi.yml
- filename: aginera-ai-projects-api-openapi.yml
  format: yaml
  label: Aginera Projects API
  slug: aginera-ai-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aginera-ai/openapi/aginera-ai-projects-api-openapi.yml
- filename: aginera-ai-reference-api-openapi.yml
  format: yaml
  label: Aginera Reference API
  slug: aginera-ai-reference-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aginera-ai/openapi/aginera-ai-reference-api-openapi.yml
- filename: aginera-ai-takeoffs-api-openapi.yml
  format: yaml
  label: Aginera Takeoffs API
  slug: aginera-ai-takeoffs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aginera-ai/openapi/aginera-ai-takeoffs-api-openapi.yml
- filename: aginera-ai-usage-api-openapi.yml
  format: yaml
  label: Aginera Usage API
  slug: aginera-ai-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aginera-ai/openapi/aginera-ai-usage-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Services are offered for business and commercial use.
    type: business
  minimum_age:
    text: You must be legally able to enter into a binding contract in your jurisdiction.
    value: null
  restricted_uses:
  - summary: No consumer use
    text: You represent that you are using the Services for commercial purposes and not primarily for personal, family, or household use.
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
name: Aginera
provenance_date: '2026-11-09'
provider_name: Aginera
provider_slug: aginera-ai
slug: aginera-ai-eligibility
source_date: '2026-11-09'
source_filename: aginera-ai-eligibility.yml
source_heading: Eligibility
source_page: https://aginera.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Aginera\naid: aginera-ai\nurl: https://aginera.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The Services are offered for business and commercial use.\nrestricted_uses:\n- summary: No consumer use\n  text: You represent that you are using the Services for commercial purposes and not primarily for personal, family,\n    or household use.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: You must be legally able to enter into a binding contract in your jurisdiction.\n"
source_yaml_url: https://artifacts.apis.io/aginera-ai/eligibility/aginera-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Aginera's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Construction
- Estimating
- MEP
- Software
---
