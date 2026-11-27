---
api_specs:
- filename: workflows
  format: yaml
  label: Xceptor Workflow API
  slug: xceptor-workflow-api
  spec_type: Postman
  url: https://www.postman.com/xceptor/workspace/workflows
- filename: xceptor-authentication-api-openapi.yml
  format: yaml
  label: Xceptor Authentication API
  slug: xceptor-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xceptor/openapi/xceptor-authentication-api-openapi.yml
- filename: xceptor-data-sources-api-openapi.yml
  format: yaml
  label: Xceptor Data Sources API
  slug: xceptor-data-sources-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xceptor/openapi/xceptor-data-sources-api-openapi.yml
- filename: xceptor-documents-api-openapi.yml
  format: yaml
  label: Xceptor Documents API
  slug: xceptor-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xceptor/openapi/xceptor-documents-api-openapi.yml
- filename: xceptor-extraction-api-openapi.yml
  format: yaml
  label: Xceptor Extraction API
  slug: xceptor-extraction-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xceptor/openapi/xceptor-extraction-api-openapi.yml
- filename: xceptor-health-api-openapi.yml
  format: yaml
  label: Xceptor Health API
  slug: xceptor-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xceptor/openapi/xceptor-health-api-openapi.yml
- filename: xceptor-jobs-api-openapi.yml
  format: yaml
  label: Xceptor Jobs API
  slug: xceptor-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xceptor/openapi/xceptor-jobs-api-openapi.yml
- filename: xceptor-templates-api-openapi.yml
  format: yaml
  label: Xceptor Templates API
  slug: xceptor-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xceptor/openapi/xceptor-templates-api-openapi.yml
- filename: xceptor-workflow-runs-api-openapi.yml
  format: yaml
  label: Xceptor Workflow Runs API
  slug: xceptor-workflow-runs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xceptor/openapi/xceptor-workflow-runs-api-openapi.yml
- filename: xceptor-workflow-steps-api-openapi.yml
  format: yaml
  label: Xceptor Workflow Steps API
  slug: xceptor-workflow-steps-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xceptor/openapi/xceptor-workflow-steps-api-openapi.yml
- filename: xceptor-workflows-api-openapi.yml
  format: yaml
  label: Xceptor Workflows API
  slug: xceptor-workflows-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xceptor/openapi/xceptor-workflows-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: We do not represent or warrant that the Website or any information contained within it is appropriate or lawful in locations outside the United Kingdom.
  entity_types:
  - text: We believe that you are not acting in a personal capacity
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No malicious code or hacking
    text: You must not attempt to gain unauthorized access to the Website, the server on which the Website is stored or any server, computer or database connected to our site.
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
name: Xceptor
provenance_date: '2026-11-10'
provider_name: Xceptor
provider_slug: xceptor
slug: xceptor-eligibility
source_date: '2026-11-10'
source_filename: xceptor-eligibility.yml
source_heading: Eligibility
source_page: https://www.xceptor.com/legal-tcs
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Xceptor\naid: xceptor\nurl: https://www.xceptor.com/legal-tcs\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: We do not represent or warrant that the Website or any information contained within it is appropriate or\n    lawful in locations outside the United Kingdom.\nentity_types:\n- type: individual\n  text: We believe that you are not acting in a personal capacity\nrestricted_uses:\n- summary: No malicious code or hacking\n  text: You must not attempt to gain unauthorized access to the Website, the server on which the Website is stored\n    or any server, computer or database\
  \ connected to our site.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/xceptor/eligibility/xceptor-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Xceptor's own page on 2026-11-10.
synthetic: false
tags:
- API Integration
- Data Automation
- Data Extraction
- Document Processing
- ETL
- Financial Data
- Financial Services
- Intelligent Document Processing
- Reconciliation
- Trade Operations
---
