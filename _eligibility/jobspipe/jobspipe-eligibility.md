---
api_specs:
- filename: jobspipe-account-api-openapi.yml
  format: yaml
  label: JobsPipe Account API
  slug: jobspipe-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jobspipe/openapi/jobspipe-account-api-openapi.yml
- filename: jobspipe-billing-api-openapi.yml
  format: yaml
  label: JobsPipe Billing API
  slug: jobspipe-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jobspipe/openapi/jobspipe-billing-api-openapi.yml
- filename: jobspipe-companies-api-openapi.yml
  format: yaml
  label: JobsPipe Companies API
  slug: jobspipe-companies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jobspipe/openapi/jobspipe-companies-api-openapi.yml
- filename: jobspipe-jobs-api-openapi.yml
  format: yaml
  label: JobsPipe Jobs API
  slug: jobspipe-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jobspipe/openapi/jobspipe-jobs-api-openapi.yml
- filename: jobspipe-labour-market-insights-api-openapi.yml
  format: yaml
  label: JobsPipe Labour Market Insights API
  slug: jobspipe-labour-market-insights-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jobspipe/openapi/jobspipe-labour-market-insights-api-openapi.yml
- filename: jobspipe-monitors-api-openapi.yml
  format: yaml
  label: JobsPipe Monitors API
  slug: jobspipe-monitors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jobspipe/openapi/jobspipe-monitors-api-openapi.yml
- filename: jobspipe-sandbox-api-openapi.yml
  format: yaml
  label: JobsPipe Sandbox API
  slug: jobspipe-sandbox-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jobspipe/openapi/jobspipe-sandbox-api-openapi.yml
- filename: jobspipe-stack-api-openapi.yml
  format: yaml
  label: JobsPipe Stack API
  slug: jobspipe-stack-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jobspipe/openapi/jobspipe-stack-api-openapi.yml
- filename: jobspipe-technologies-api-openapi.yml
  format: yaml
  label: JobsPipe Technologies API
  slug: jobspipe-technologies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jobspipe/openapi/jobspipe-technologies-api-openapi.yml
- filename: jobspipe-contacts-api-openapi.yml
  format: yaml
  label: JobsPipe Contacts API
  slug: jobspipe-contacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jobspipe/openapi/jobspipe-contacts-api-openapi.yml
- filename: jobspipe-layoffs-api-openapi.yml
  format: yaml
  label: JobsPipe Layoffs API
  slug: jobspipe-layoffs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jobspipe/openapi/jobspipe-layoffs-api-openapi.yml
- filename: jobspipe-live-api-openapi.yml
  format: yaml
  label: JobsPipe Live API
  slug: jobspipe-live-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jobspipe/openapi/jobspipe-live-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Discrimination against candidates or profiling
    text: use the data to discriminate against candidates or to monitor or profile individuals
  - source: https://jobspipe.dev/terms.md
    summary: Discrimination or profiling
    text: use the data to discriminate against candidates or to monitor or profile individuals
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
name: JobsPipe
provenance_date: '2026-11-09'
provider_name: JobsPipe
provider_slug: jobspipe
slug: jobspipe-eligibility
source_date: '2026-11-09'
source_filename: jobspipe-eligibility.yml
source_heading: Eligibility
source_page: https://jobspipe.dev/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: JobsPipe\naid: jobspipe\nurl: https://jobspipe.dev/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://jobspipe.dev/terms\n  - https://jobspipe.dev/terms.md\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Discrimination against candidates or profiling\n  text: use the data to discriminate against candidates or to monitor or profile individuals\n- summary: Discrimination or profiling\n  text: use the data to discriminate against candidates or to monitor or profile individuals\n  source: https://jobspipe.dev/terms.md\nverification:\n  kyc: null\n  kyb:\
  \ null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/jobspipe/eligibility/jobspipe-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 2 quoted statements, read from JobsPipe's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Job
- Data
- Hiring
- JobsAPI
---
