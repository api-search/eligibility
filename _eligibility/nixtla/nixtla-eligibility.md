---
api_specs:
- filename: nixtla-anomaly-detection-api-openapi.yml
  format: yaml
  label: Nixtla Anomaly Detection API
  slug: nixtla-anomaly-detection-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nixtla/openapi/nixtla-anomaly-detection-api-openapi.yml
- filename: nixtla-cross-validation-api-openapi.yml
  format: yaml
  label: Nixtla Cross Validation API
  slug: nixtla-cross-validation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nixtla/openapi/nixtla-cross-validation-api-openapi.yml
- filename: nixtla-excluded-api-openapi.yml
  format: yaml
  label: Nixtla Excluded API
  slug: nixtla-excluded-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nixtla/openapi/nixtla-excluded-api-openapi.yml
- filename: nixtla-finetune-api-openapi.yml
  format: yaml
  label: Nixtla Finetune API
  slug: nixtla-finetune-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nixtla/openapi/nixtla-finetune-api-openapi.yml
- filename: nixtla-finetuned-models-api-openapi.yml
  format: yaml
  label: Nixtla Finetuned Models API
  slug: nixtla-finetuned-models-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nixtla/openapi/nixtla-finetuned-models-api-openapi.yml
- filename: nixtla-forecast-api-openapi.yml
  format: yaml
  label: Nixtla Forecast API
  slug: nixtla-forecast-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nixtla/openapi/nixtla-forecast-api-openapi.yml
- filename: nixtla-online-anomaly-detection-api-openapi.yml
  format: yaml
  label: Nixtla Online Anomaly Detection API
  slug: nixtla-online-anomaly-detection-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nixtla/openapi/nixtla-online-anomaly-detection-api-openapi.yml
- filename: nixtla-validate-api-key-api-openapi.yml
  format: yaml
  label: Nixtla Validate Api Key API
  slug: nixtla-validate-api-key-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nixtla/openapi/nixtla-validate-api-key-api-openapi.yml
claim_count: 7
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You may use Services only in geographies currently supported by Nixtla.
  entity_types:
  - text: You must be at least 13 years old to use the Services.
    type: individual
  - text: If you use the Services on behalf of another person or entity, you must have the authority to accept the Terms on their behalf.
    type: business
  minimum_age:
    text: You must be at least 13 years old to use the Services. If you are under 18 you must have your parent or legal guardian’s permission to use the Services.
    value: '13'
  restricted_uses:
  - summary: Export controls
    text: The Services may not be used in or for the benefit of, exported, or re-exported (a) into any U.S. embargoed countries
  - summary: Children's personal information
    text: (vii), send us any personal information of children under 13 or the applicable age of consent.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You must provide accurate and complete information to register for an account.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Nixtla
provenance_date: '2026-11-10'
provider_name: Nixtla
provider_slug: nixtla
slug: nixtla-eligibility
source_date: '2026-11-10'
source_filename: nixtla-eligibility.yml
source_heading: Eligibility
source_page: https://www.nixtla.io/docs/about/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Nixtla\naid: nixtla\nurl: https://www.nixtla.io/docs/about/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You may use Services only in geographies currently supported by Nixtla.\nentity_types:\n- type: individual\n  text: You must be at least 13 years old to use the Services.\n- type: business\n  text: If you use the Services on behalf of another person or entity, you must have the authority to accept the\n    Terms on their behalf.\nrestricted_uses:\n- summary: Export controls\n  text: The Services may not be used in or for the benefit of, exported, or re-exported\
  \ (a) into any U.S. embargoed\n    countries\n- summary: Children's personal information\n  text: (vii), send us any personal information of children under 13 or the applicable age of consent.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You must provide accurate and complete information to register for an account.\nminimum_age:\n  value: '13'\n  text: You must be at least 13 years old to use the Services. If you are under 18 you must have your parent or\n    legal guardian’s permission to use the Services.\n"
source_yaml_url: https://artifacts.apis.io/nixtla/eligibility/nixtla-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 7 quoted statements, read from Nixtla's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Time Series
- Forecasting
- Anomaly Detection
- Machine Learning
- Artificial Intelligence
- Foundation Models
- Predictive Analytics
- Data Science
---
