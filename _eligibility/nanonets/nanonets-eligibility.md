---
api_specs:
- filename: nanonets-external-integrations-api-openapi.yml
  format: yaml
  label: Nanonets External Integrations API
  slug: nanonets-external-integrations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nanonets/openapi/nanonets-external-integrations-api-openapi.yml
- filename: nanonets-file-assignment-api-openapi.yml
  format: yaml
  label: Nanonets File Assignment API
  slug: nanonets-file-assignment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nanonets/openapi/nanonets-file-assignment-api-openapi.yml
- filename: nanonets-file-delete-api-openapi.yml
  format: yaml
  label: Nanonets File Delete API
  slug: nanonets-file-delete-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nanonets/openapi/nanonets-file-delete-api-openapi.yml
- filename: nanonets-file-export-api-openapi.yml
  format: yaml
  label: Nanonets File Export API
  slug: nanonets-file-export-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nanonets/openapi/nanonets-file-export-api-openapi.yml
- filename: nanonets-file-review-api-openapi.yml
  format: yaml
  label: Nanonets File Review API
  slug: nanonets-file-review-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nanonets/openapi/nanonets-file-review-api-openapi.yml
- filename: nanonets-file-update-api-openapi.yml
  format: yaml
  label: Nanonets File Update API
  slug: nanonets-file-update-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nanonets/openapi/nanonets-file-update-api-openapi.yml
- filename: nanonets-image-classification-predict-api-openapi.yml
  format: yaml
  label: Nanonets Image Classification Predict API
  slug: nanonets-image-classification-predict-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nanonets/openapi/nanonets-image-classification-predict-api-openapi.yml
- filename: nanonets-ocr-predict-api-openapi.yml
  format: yaml
  label: Nanonets OCR Predict API
  slug: nanonets-ocr-predict-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nanonets/openapi/nanonets-ocr-predict-api-openapi.yml
- filename: nanonets-ocr-retrieve-api-openapi.yml
  format: yaml
  label: Nanonets OCR Retrieve API
  slug: nanonets-ocr-retrieve-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nanonets/openapi/nanonets-ocr-retrieve-api-openapi.yml
- filename: nanonets-ocr-train-api-openapi.yml
  format: yaml
  label: Nanonets OCR Train API
  slug: nanonets-ocr-train-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nanonets/openapi/nanonets-ocr-train-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: YOU REPRESENT AND WARRANT THAT (A) YOU ARE AT LEAST 18 YEARS OF AGE; (B) YOU HAVE THE AUTHORITY TO ENTER INTO THIS AGREEMENT
    type: individual
  - text: IF YOU ARE ENTERING INTO THIS AGREEMENT ON BEHALF OF AN ORGANIZATION OR ENTITY, YOU REPRESENT THAT YOU HAVE THE AUTHORITY TO BIND SUCH ENTITY AND ITS AFFILIATES TO THESE TERMS
    type: business
  minimum_age:
    text: YOU REPRESENT AND WARRANT THAT (A) YOU ARE AT LEAST 18 YEARS OF AGE
    value: '18'
  restricted_uses:
  - summary: Compliance with laws and privacy
    text: Customer will use the Services only in accordance with all applicable laws, including, but not limited to, laws related to data protection and privacy
  - summary: US export control
    text: Customer hereby certifies that Customer will comply with all current US Export Control laws.
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
name: Nanonets
provenance_date: '2026-11-10'
provider_name: Nanonets
provider_slug: nanonets
slug: nanonets-eligibility
source_date: '2026-11-10'
source_filename: nanonets-eligibility.yml
source_heading: Eligibility
source_page: https://legal.nanonets.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Nanonets\naid: nanonets\nurl: https://legal.nanonets.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: YOU REPRESENT AND WARRANT THAT (A) YOU ARE AT LEAST 18 YEARS OF AGE; (B) YOU HAVE THE AUTHORITY TO ENTER\n    INTO THIS AGREEMENT\n- type: business\n  text: IF YOU ARE ENTERING INTO THIS AGREEMENT ON BEHALF OF AN ORGANIZATION OR ENTITY, YOU REPRESENT THAT YOU HAVE\n    THE AUTHORITY TO BIND SUCH ENTITY AND ITS AFFILIATES TO THESE TERMS\nrestricted_uses:\n- summary: Compliance with laws and privacy\n  text: Customer will use\
  \ the Services only in accordance with all applicable laws, including, but not limited to,\n    laws related to data protection and privacy\n- summary: US export control\n  text: Customer hereby certifies that Customer will comply with all current US Export Control laws.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: YOU REPRESENT AND WARRANT THAT (A) YOU ARE AT LEAST 18 YEARS OF AGE\n"
source_yaml_url: https://artifacts.apis.io/nanonets/eligibility/nanonets-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Nanonets's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- OCR
- Document AI
- Intelligent Document Processing
- Data Extraction
- Workflow Automation
- Computer Vision
- No-Code
---
