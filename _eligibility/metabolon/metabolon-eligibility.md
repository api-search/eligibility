---
api_specs:
- filename: metabolon-assistant-api-openapi.yml
  format: yaml
  label: Metabolon Assistant API
  slug: metabolon-assistant-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/metabolon/openapi/metabolon-assistant-api-openapi.yml
- filename: metabolon-auth-api-openapi.yml
  format: yaml
  label: Metabolon Auth API
  slug: metabolon-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/metabolon/openapi/metabolon-auth-api-openapi.yml
- filename: metabolon-decentralization-api-openapi.yml
  format: yaml
  label: Metabolon Decentralization API
  slug: metabolon-decentralization-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/metabolon/openapi/metabolon-decentralization-api-openapi.yml
- filename: metabolon-eula-api-openapi.yml
  format: yaml
  label: Metabolon Eula API
  slug: metabolon-eula-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/metabolon/openapi/metabolon-eula-api-openapi.yml
- filename: metabolon-files-api-openapi.yml
  format: yaml
  label: Metabolon Files API
  slug: metabolon-files-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/metabolon/openapi/metabolon-files-api-openapi.yml
- filename: metabolon-health-api-openapi.yml
  format: yaml
  label: Metabolon Health API
  slug: metabolon-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/metabolon/openapi/metabolon-health-api-openapi.yml
- filename: metabolon-labvantagefiles-api-openapi.yml
  format: yaml
  label: Metabolon Lab Vantage Files API
  slug: metabolon-labvantagefiles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/metabolon/openapi/metabolon-labvantagefiles-api-openapi.yml
- filename: metabolon-projects-api-openapi.yml
  format: yaml
  label: Metabolon Projects API
  slug: metabolon-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/metabolon/openapi/metabolon-projects-api-openapi.yml
- filename: metabolon-reports-api-openapi.yml
  format: yaml
  label: Metabolon Reports API
  slug: metabolon-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/metabolon/openapi/metabolon-reports-api-openapi.yml
- filename: metabolon-samplesets-api-openapi.yml
  format: yaml
  label: Metabolon Sample Sets API
  slug: metabolon-samplesets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/metabolon/openapi/metabolon-samplesets-api-openapi.yml
- filename: metabolon-samplesetsinfo-api-openapi.yml
  format: yaml
  label: Metabolon Sample Sets Info API
  slug: metabolon-samplesetsinfo-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/metabolon/openapi/metabolon-samplesetsinfo-api-openapi.yml
- filename: metabolon-search-api-openapi.yml
  format: yaml
  label: Metabolon Search API
  slug: metabolon-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/metabolon/openapi/metabolon-search-api-openapi.yml
- filename: metabolon-sharedfile-api-openapi.yml
  format: yaml
  label: Metabolon Shared File API
  slug: metabolon-sharedfile-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/metabolon/openapi/metabolon-sharedfile-api-openapi.yml
- filename: metabolon-spectraldata-api-openapi.yml
  format: yaml
  label: Metabolon Spectral Data API
  slug: metabolon-spectraldata-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/metabolon/openapi/metabolon-spectraldata-api-openapi.yml
- filename: metabolon-status-api-openapi.yml
  format: yaml
  label: Metabolon Status API
  slug: metabolon-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/metabolon/openapi/metabolon-status-api-openapi.yml
- filename: metabolon-studybuilder-api-openapi.yml
  format: yaml
  label: Metabolon Study Builder API
  slug: metabolon-studybuilder-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/metabolon/openapi/metabolon-studybuilder-api-openapi.yml
- filename: metabolon-users-api-openapi.yml
  format: yaml
  label: Metabolon Users API
  slug: metabolon-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/metabolon/openapi/metabolon-users-api-openapi.yml
- filename: metabolon-pipeline-status-api-openapi.yml
  format: yaml
  label: Metabolon Pipeline Status API
  slug: metabolon-pipeline-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/metabolon/openapi/metabolon-pipeline-status-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: It is not our intention to collect personal information from children under the age of 18 through the Site.
    value: '18'
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
name: Metabolon
provenance_date: '2026-11-10'
provider_name: Metabolon
provider_slug: metabolon
slug: metabolon-eligibility
source_date: '2026-11-10'
source_filename: metabolon-eligibility.yml
source_heading: Eligibility
source_page: https://www.metabolon.com/legal/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Metabolon\naid: metabolon\nurl: https://www.metabolon.com/legal/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: It is not our intention to collect personal information from children under the age of 18 through the Site.\n"
source_yaml_url: https://artifacts.apis.io/metabolon/eligibility/metabolon-eligibility.yml
stated_fields:
- minimum_age
summary_line: 1 quoted statement, read from Metabolon's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Metabolomics
- Life Sciences
- Bioinformatics
- Multiomics
- Biotechnology
- Drug Discovery
- Precision Medicine
- Microbiome
- Biomarkers
- Contract Research
- Laboratory
---
