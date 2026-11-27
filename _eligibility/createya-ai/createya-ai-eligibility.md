---
api_specs:
- filename: createya-ai-balance-api-openapi.yml
  format: yaml
  label: Createya Balance API
  slug: createya-ai-balance-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/createya-ai/openapi/createya-ai-balance-api-openapi.yml
- filename: createya-ai-healthz-api-openapi.yml
  format: yaml
  label: Createya Healthz API
  slug: createya-ai-healthz-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/createya-ai/openapi/createya-ai-healthz-api-openapi.yml
- filename: createya-ai-mcp-api-openapi.yml
  format: yaml
  label: Createya MCP API
  slug: createya-ai-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/createya-ai/openapi/createya-ai-mcp-api-openapi.yml
- filename: createya-ai-models-api-openapi.yml
  format: yaml
  label: Createya Models API
  slug: createya-ai-models-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/createya-ai/openapi/createya-ai-models-api-openapi.yml
- filename: createya-ai-run-api-openapi.yml
  format: yaml
  label: Createya Run API
  slug: createya-ai-run-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/createya-ai/openapi/createya-ai-run-api-openapi.yml
- filename: createya-ai-runs-api-openapi.yml
  format: yaml
  label: Createya Runs API
  slug: createya-ai-runs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/createya-ai/openapi/createya-ai-runs-api-openapi.yml
- filename: createya-ai-uploads-api-openapi.yml
  format: yaml
  label: Createya Uploads API
  slug: createya-ai-uploads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/createya-ai/openapi/createya-ai-uploads-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: в адрес любого физического или юридического лица
    type: business
  minimum_age:
    text: Лицам, не достигшим возраста четырнадцати (14) лет, доступ к Сервису не предоставляется.
    value: '14'
  restricted_uses:
  - summary: Deepfakes of real people
    text: Контент, представляющий собой дипфейки (deepfakes) — реалистичные изображения или видео реальных людей без их явно выраженного согласия
  - summary: Sexual content involving minors
    text: Контент, содержащий сексуальную эксплуатацию несовершеннолетних или изображения несовершеннолетних в сексуальном контексте.
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
name: Createya
provenance_date: '2026-11-09'
provider_name: Createya
provider_slug: createya-ai
slug: createya-ai-eligibility
source_date: '2026-11-09'
source_filename: createya-ai-eligibility.yml
source_heading: Eligibility
source_page: https://createya.ai/offer/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Createya\naid: createya-ai\nurl: https://createya.ai/offer/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: в адрес любого физического или юридического лица\nrestricted_uses:\n- summary: Deepfakes of real people\n  text: Контент, представляющий собой дипфейки (deepfakes) — реалистичные изображения или видео реальных людей без\n    их явно выраженного согласия\n- summary: Sexual content involving minors\n  text: Контент, содержащий сексуальную эксплуатацию несовершеннолетних или изображения несовершеннолетних в сексуальном\n    контексте.\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '14'\n  text: Лицам, не достигшим возраста четырнадцати (14) лет, доступ к Сервису не предоставляется.\n"
source_yaml_url: https://artifacts.apis.io/createya-ai/eligibility/createya-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Createya's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Generative AI
- Image Generation
- Video Generation
- Audio Generation
- Model Aggregator
- MCP
---
