---
api_specs:
- filename: oxen-ai-api-openapi.yml
  format: yaml
  label: Oxen Ai API
  slug: oxen-ai-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/oxen/openapi/oxen-ai-api-openapi.yml
- filename: oxen-branches-api-openapi.yml
  format: yaml
  label: Oxen Branches API
  slug: oxen-branches-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/oxen/openapi/oxen-branches-api-openapi.yml
- filename: oxen-commits-api-openapi.yml
  format: yaml
  label: Oxen Commits API
  slug: oxen-commits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/oxen/openapi/oxen-commits-api-openapi.yml
- filename: oxen-compare-api-openapi.yml
  format: yaml
  label: Oxen Compare API
  slug: oxen-compare-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/oxen/openapi/oxen-compare-api-openapi.yml
- filename: oxen-data-frames-api-openapi.yml
  format: yaml
  label: Oxen Data Frames API
  slug: oxen-data-frames-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/oxen/openapi/oxen-data-frames-api-openapi.yml
- filename: oxen-directories-api-openapi.yml
  format: yaml
  label: Oxen Directories API
  slug: oxen-directories-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/oxen/openapi/oxen-directories-api-openapi.yml
- filename: oxen-evaluations-api-openapi.yml
  format: yaml
  label: Oxen Evaluations API
  slug: oxen-evaluations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/oxen/openapi/oxen-evaluations-api-openapi.yml
- filename: oxen-export-api-openapi.yml
  format: yaml
  label: Oxen Export API
  slug: oxen-export-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/oxen/openapi/oxen-export-api-openapi.yml
- filename: oxen-files-api-openapi.yml
  format: yaml
  label: Oxen Files API
  slug: oxen-files-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/oxen/openapi/oxen-files-api-openapi.yml
- filename: oxen-fine-tunes-api-openapi.yml
  format: yaml
  label: Oxen Fine Tunes API
  slug: oxen-fine-tunes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/oxen/openapi/oxen-fine-tunes-api-openapi.yml
- filename: oxen-health-api-openapi.yml
  format: yaml
  label: Oxen Health API
  slug: oxen-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/oxen/openapi/oxen-health-api-openapi.yml
- filename: oxen-import-api-openapi.yml
  format: yaml
  label: Oxen Import API
  slug: oxen-import-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/oxen/openapi/oxen-import-api-openapi.yml
- filename: oxen-merge-api-openapi.yml
  format: yaml
  label: Oxen Merge API
  slug: oxen-merge-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/oxen/openapi/oxen-merge-api-openapi.yml
- filename: oxen-metadata-api-openapi.yml
  format: yaml
  label: Oxen Metadata API
  slug: oxen-metadata-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/oxen/openapi/oxen-metadata-api-openapi.yml
- filename: oxen-namespaces-api-openapi.yml
  format: yaml
  label: Oxen Namespaces API
  slug: oxen-namespaces-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/oxen/openapi/oxen-namespaces-api-openapi.yml
- filename: oxen-repositories-api-openapi.yml
  format: yaml
  label: Oxen Repositories API
  slug: oxen-repositories-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/oxen/openapi/oxen-repositories-api-openapi.yml
- filename: oxen-version-files-api-openapi.yml
  format: yaml
  label: Oxen Version Files API
  slug: oxen-version-files-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/oxen/openapi/oxen-version-files-api-openapi.yml
- filename: oxen-workspace-files-api-openapi.yml
  format: yaml
  label: Oxen Workspace Files API
  slug: oxen-workspace-files-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/oxen/openapi/oxen-workspace-files-api-openapi.yml
- filename: oxen-workspaces-api-openapi.yml
  format: yaml
  label: Oxen Workspaces API
  slug: oxen-workspaces-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/oxen/openapi/oxen-workspaces-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You represent and warrant that you are at least 16 years of age or older.
    value: '16'
  restricted_uses:
  - summary: No fraudulent or illegal activity
    text: for any illegal or fraudulent activity
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
name: Oxen
provenance_date: '2026-11-10'
provider_name: Oxen
provider_slug: oxen
slug: oxen-eligibility
source_date: '2026-11-10'
source_filename: oxen-eligibility.yml
source_heading: Eligibility
source_page: https://www.oxen.ai/legal/evaluation-terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Oxen\naid: oxen\nurl: https://www.oxen.ai/legal/evaluation-terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: No fraudulent or illegal activity\n  text: for any illegal or fraudulent activity\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: You represent and warrant that you are at least 16 years of age or older.\n"
source_yaml_url: https://artifacts.apis.io/oxen/eligibility/oxen-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Oxen's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Data Version Control
- Machine Learning
- Artificial Intelligence
- Fine-Tuning
- Inference
- Datasets
- MLOps
- LLM
- Model Deployment
- Developer Tools
- Version Control
---
