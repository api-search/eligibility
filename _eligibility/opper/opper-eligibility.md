---
api_specs:
- filename: opper-account-api-openapi.yml
  format: yaml
  label: Opper AI Account API
  slug: opper-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/opper/openapi/opper-account-api-openapi.yml
- filename: opper-artifacts-api-openapi.yml
  format: yaml
  label: Opper AI Artifacts API
  slug: opper-artifacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/opper/openapi/opper-artifacts-api-openapi.yml
- filename: opper-audio-api-openapi.yml
  format: yaml
  label: Opper AI Audio API
  slug: opper-audio-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/opper/openapi/opper-audio-api-openapi.yml
- filename: opper-compatibility-api-openapi.yml
  format: yaml
  label: Opper AI Compatibility API
  slug: opper-compatibility-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/opper/openapi/opper-compatibility-api-openapi.yml
- filename: opper-files-api-openapi.yml
  format: yaml
  label: Opper AI Files API
  slug: opper-files-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/opper/openapi/opper-files-api-openapi.yml
- filename: opper-functions-api-openapi.yml
  format: yaml
  label: Opper AI Functions API
  slug: opper-functions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/opper/openapi/opper-functions-api-openapi.yml
- filename: opper-generations-api-openapi.yml
  format: yaml
  label: Opper AI Generations API
  slug: opper-generations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/opper/openapi/opper-generations-api-openapi.yml
- filename: opper-images-api-openapi.yml
  format: yaml
  label: Opper AI Images API
  slug: opper-images-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/opper/openapi/opper-images-api-openapi.yml
- filename: opper-management-api-openapi.yml
  format: yaml
  label: Opper AI Management API
  slug: opper-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/opper/openapi/opper-management-api-openapi.yml
- filename: opper-models-api-openapi.yml
  format: yaml
  label: Opper AI Models API
  slug: opper-models-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/opper/openapi/opper-models-api-openapi.yml
- filename: opper-ocr-api-openapi.yml
  format: yaml
  label: Opper AI OCR API
  slug: opper-ocr-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/opper/openapi/opper-ocr-api-openapi.yml
- filename: opper-rerank-api-openapi.yml
  format: yaml
  label: Opper AI Rerank API
  slug: opper-rerank-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/opper/openapi/opper-rerank-api-openapi.yml
- filename: opper-roundtable-api-openapi.yml
  format: yaml
  label: Opper AI Roundtable API
  slug: opper-roundtable-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/opper/openapi/opper-roundtable-api-openapi.yml
- filename: opper-spans-api-openapi.yml
  format: yaml
  label: Opper AI Spans API
  slug: opper-spans-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/opper/openapi/opper-spans-api-openapi.yml
- filename: opper-system-api-openapi.yml
  format: yaml
  label: Opper AI System API
  slug: opper-system-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/opper/openapi/opper-system-api-openapi.yml
- filename: opper-tools-api-openapi.yml
  format: yaml
  label: Opper AI Tools API
  slug: opper-tools-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/opper/openapi/opper-tools-api-openapi.yml
- filename: opper-traces-api-openapi.yml
  format: yaml
  label: Opper AI Traces API
  slug: opper-traces-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/opper/openapi/opper-traces-api-openapi.yml
- filename: opper-user-delegation-api-openapi.yml
  format: yaml
  label: Opper AI User delegation API
  slug: opper-user-delegation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/opper/openapi/opper-user-delegation-api-openapi.yml
- filename: opper-videos-api-openapi.yml
  format: yaml
  label: Opper AI Videos API
  slug: opper-videos-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/opper/openapi/opper-videos-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Any individual or legal entity (the “Customer”) accessing Opper’s AI integration platform
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Use in breach of laws or Agreement
    text: The Customer agrees to comply with all applicable local, national, and international laws and regulations while using the Platform and the Services.
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
name: Opper AI
provenance_date: '2026-11-10'
provider_name: Opper AI
provider_slug: opper
slug: opper-eligibility
source_date: '2026-11-10'
source_filename: opper-eligibility.yml
source_heading: Eligibility
source_page: https://opper.ai/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Opper AI\naid: opper\nurl: https://opper.ai/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Any individual or legal entity (the “Customer”) accessing Opper’s AI integration platform\nrestricted_uses:\n- summary: Use in breach of laws or Agreement\n  text: The Customer agrees to comply with all applicable local, national, and international laws and regulations\n    while using the Platform and the Services.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n\
  \  text: null\n"
source_yaml_url: https://artifacts.apis.io/opper/eligibility/opper-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Opper AI's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- Gateways
- European
- OpenAI-Compatible
- GDPR
---
