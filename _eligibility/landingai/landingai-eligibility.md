---
api_specs:
- filename: landingai-classes-api-openapi.yml
  format: yaml
  label: Landing.ai Classes API
  slug: landingai-classes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/landingai/openapi/landingai-classes-api-openapi.yml
- filename: landingai-deployment-api-openapi.yml
  format: yaml
  label: Landing.ai Deployment API
  slug: landingai-deployment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/landingai/openapi/landingai-deployment-api-openapi.yml
- filename: landingai-extract-api-openapi.yml
  format: yaml
  label: Landing.ai Extract API
  slug: landingai-extract-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/landingai/openapi/landingai-extract-api-openapi.yml
- filename: landingai-image-api-openapi.yml
  format: yaml
  label: Landing.ai Image API
  slug: landingai-image-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/landingai/openapi/landingai-image-api-openapi.yml
- filename: landingai-metadata-api-openapi.yml
  format: yaml
  label: Landing.ai Metadata API
  slug: landingai-metadata-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/landingai/openapi/landingai-metadata-api-openapi.yml
- filename: landingai-metrics-api-openapi.yml
  format: yaml
  label: Landing.ai Metrics API
  slug: landingai-metrics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/landingai/openapi/landingai-metrics-api-openapi.yml
- filename: landingai-model-api-openapi.yml
  format: yaml
  label: Landing.ai Model API
  slug: landingai-model-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/landingai/openapi/landingai-model-api-openapi.yml
- filename: landingai-parse-api-openapi.yml
  format: yaml
  label: Landing.ai Parse API
  slug: landingai-parse-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/landingai/openapi/landingai-parse-api-openapi.yml
- filename: landingai-project-api-openapi.yml
  format: yaml
  label: Landing.ai Project API
  slug: landingai-project-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/landingai/openapi/landingai-project-api-openapi.yml
- filename: landingai-snapshot-api-openapi.yml
  format: yaml
  label: Landing.ai Snapshot API
  slug: landingai-snapshot-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/landingai/openapi/landingai-snapshot-api-openapi.yml
- filename: landingai-tags-api-openapi.yml
  format: yaml
  label: Landing.ai Tags API
  slug: landingai-tags-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/landingai/openapi/landingai-tags-api-openapi.yml
- filename: landingai-tools-api-openapi.yml
  format: yaml
  label: Landing.ai Tools API
  slug: landingai-tools-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/landingai/openapi/landingai-tools-api-openapi.yml
- filename: landingai-training-api-openapi.yml
  format: yaml
  label: Landing.ai Training API
  slug: landingai-training-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/landingai/openapi/landingai-training-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - KP
    - SD
    - SY
    served: []
    text: Customer will not export, re-export or transfer any items or provide any Services ... to any jurisdiction subject to sanctions laws, including without limitation Cuba, Iran, North Korea, Sudan, Syria and the non-government-controlled regions of Ukraine
  entity_types:
  - text: If you are accessing and using the Services on behalf of a company (such as your employer) or other legal entity, you represent and warrant that you have the authority to bind that entity
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Not for personal data or regulated data
    text: THE SERVICES ARE NOT INTENDED FOR USE WITH PERSONAL DATA, CLASSIFIED INFORMATION OR ANY OTHER DATA OR CUSTOMER MATERIALS THAT ARE SUBJECT TO PRIVACY LAWS, EXPORT CONTROL LAWS
  - summary: Responsible AI restrictions
    text: For fully automated decision making that adversely impacts an individual's legal rights or otherwise creates or modifies a binding, enforceable obligation
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You may need to provide additional information to verify your identity before completing your Transaction
excluded_countries:
- CU
- IR
- KP
- SD
- SY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Landing.ai
provenance_date: '2026-11-09'
provider_name: Landing.ai
provider_slug: landingai
slug: landingai-eligibility
source_date: '2026-11-09'
source_filename: landingai-eligibility.yml
source_heading: Eligibility
source_page: https://www.landing.ai/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Landing.ai\naid: landingai\nurl: https://www.landing.ai/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  - SD\n  - SY\n  text: Customer will not export, re-export or transfer any items or provide any Services ... to any jurisdiction\n    subject to sanctions laws, including without limitation Cuba, Iran, North Korea, Sudan, Syria and the non-government-controlled\n    regions of Ukraine\nentity_types:\n- type: business\n  text: If you are accessing and using the Services on behalf of a company (such as your employer) or other legal\n    entity, you\
  \ represent and warrant that you have the authority to bind that entity\nrestricted_uses:\n- summary: Not for personal data or regulated data\n  text: THE SERVICES ARE NOT INTENDED FOR USE WITH PERSONAL DATA, CLASSIFIED INFORMATION OR ANY OTHER DATA OR CUSTOMER\n    MATERIALS THAT ARE SUBJECT TO PRIVACY LAWS, EXPORT CONTROL LAWS\n- summary: Responsible AI restrictions\n  text: For fully automated decision making that adversely impacts an individual's legal rights or otherwise creates\n    or modifies a binding, enforceable obligation\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You may need to provide additional information to verify your identity before completing your Transaction\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/landingai/eligibility/landingai-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 5 quoted statements, read from Landing.ai's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Machine Learning
- Document Extraction
- Document Processing
- Computer Vision
- OCR
- Data Extraction
- Agents
- Developer Tools
---
