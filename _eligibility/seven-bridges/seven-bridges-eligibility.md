---
api_specs:
- filename: seven-bridges-action-api-openapi.yml
  format: yaml
  label: Seven Bridges Action API
  slug: seven-bridges-action-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/seven-bridges/openapi/seven-bridges-action-api-openapi.yml
- filename: seven-bridges-api-settings-api-openapi.yml
  format: yaml
  label: Seven Bridges API Settings API
  slug: seven-bridges-api-settings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/seven-bridges/openapi/seven-bridges-api-settings-api-openapi.yml
- filename: seven-bridges-apps-api-openapi.yml
  format: yaml
  label: Seven Bridges Apps API
  slug: seven-bridges-apps-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/seven-bridges/openapi/seven-bridges-apps-api-openapi.yml
- filename: seven-bridges-billing-api-openapi.yml
  format: yaml
  label: Seven Bridges Billing API
  slug: seven-bridges-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/seven-bridges/openapi/seven-bridges-billing-api-openapi.yml
- filename: seven-bridges-bulk-api-openapi.yml
  format: yaml
  label: Seven Bridges Bulk API
  slug: seven-bridges-bulk-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/seven-bridges/openapi/seven-bridges-bulk-api-openapi.yml
- filename: seven-bridges-files-api-openapi.yml
  format: yaml
  label: Seven Bridges Files API
  slug: seven-bridges-files-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/seven-bridges/openapi/seven-bridges-files-api-openapi.yml
- filename: seven-bridges-https-api-openapi.yml
  format: yaml
  label: 'Seven Bridges Https: API'
  slug: seven-bridges-https-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/seven-bridges/openapi/seven-bridges-https-api-openapi.yml
- filename: seven-bridges-projects-api-openapi.yml
  format: yaml
  label: Seven Bridges Projects API
  slug: seven-bridges-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/seven-bridges/openapi/seven-bridges-projects-api-openapi.yml
- filename: seven-bridges-rate-limit-api-openapi.yml
  format: yaml
  label: Seven Bridges Rate Limit API
  slug: seven-bridges-rate-limit-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/seven-bridges/openapi/seven-bridges-rate-limit-api-openapi.yml
- filename: seven-bridges-search-api-openapi.yml
  format: yaml
  label: Seven Bridges Search API
  slug: seven-bridges-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/seven-bridges/openapi/seven-bridges-search-api-openapi.yml
- filename: seven-bridges-seven-bridges-platform-api-openapi.yml
  format: yaml
  label: Seven Bridges Seven Bridges Platform API
  slug: seven-bridges-seven-bridges-platform-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/seven-bridges/openapi/seven-bridges-seven-bridges-platform-api-openapi.yml
- filename: seven-bridges-storage-api-openapi.yml
  format: yaml
  label: Seven Bridges Storage API
  slug: seven-bridges-storage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/seven-bridges/openapi/seven-bridges-storage-api-openapi.yml
- filename: seven-bridges-tasks-api-openapi.yml
  format: yaml
  label: Seven Bridges Tasks API
  slug: seven-bridges-tasks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/seven-bridges/openapi/seven-bridges-tasks-api-openapi.yml
- filename: seven-bridges-upload-api-openapi.yml
  format: yaml
  label: Seven Bridges Upload API
  slug: seven-bridges-upload-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/seven-bridges/openapi/seven-bridges-upload-api-openapi.yml
- filename: seven-bridges-user-api-openapi.yml
  format: yaml
  label: Seven Bridges User API
  slug: seven-bridges-user-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/seven-bridges/openapi/seven-bridges-user-api-openapi.yml
- filename: seven-bridges-users-api-openapi.yml
  format: yaml
  label: Seven Bridges Users API
  slug: seven-bridges-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/seven-bridges/openapi/seven-bridges-users-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: We make no representation that information on our Services is appropriate or available for use outside the United States.
  minimum_age:
    text: The Services are not intended for use by children under the age of 13. You represent and warrant that you are at least 13 years of age.
    value: '13'
  restricted_uses:
  - summary: Diagnosis or treatment
    text: THE SERVICES ARE SOLELY FOR USE IN RESEARCH AND EDUCATIONAL USE, NOT FOR ANY DIAGNOSIS OR TREATMENT OF ANY HUMAN DISEASE OR CONDITION.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: In order to use the Services, we ask you to complete a registration form, choose a username, provide an email address, and create a password
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Seven Bridges
provenance_date: '2026-11-10'
provider_name: Seven Bridges
provider_slug: seven-bridges
slug: seven-bridges-eligibility
source_date: '2026-11-10'
source_filename: seven-bridges-eligibility.yml
source_heading: Eligibility
source_page: https://www.sevenbridges.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Seven Bridges\naid: seven-bridges\nurl: https://www.sevenbridges.com/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: We make no representation that information on our Services is appropriate or available for use outside the\n    United States.\nentity_types: []\nrestricted_uses:\n- summary: Diagnosis or treatment\n  text: THE SERVICES ARE SOLELY FOR USE IN RESEARCH AND EDUCATIONAL USE, NOT FOR ANY DIAGNOSIS OR TREATMENT OF ANY\n    HUMAN DISEASE OR CONDITION.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: In order to use the Services,\
  \ we ask you to complete a registration form, choose a username, provide an\n    email address, and create a password\nminimum_age:\n  value: '13'\n  text: The Services are not intended for use by children under the age of 13. You represent and warrant that you\n    are at least 13 years of age.\n"
source_yaml_url: https://artifacts.apis.io/seven-bridges/eligibility/seven-bridges-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Seven Bridges's own page on 2026-11-10.
synthetic: false
tags:
- Genomics
- Bioinformatics
- Life Sciences
- Healthcare
- Cloud Computing
- Data Analysis
- Workflow Automation
- Research
- Precision Medicine
- Common Workflow Language
- File Storage
- Company
---
