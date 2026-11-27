---
api_specs:
- filename: google-cloud-logging-exclusions-api-openapi.yml
  format: yaml
  label: Google Cloud Logging Exclusions API
  slug: google-cloud-logging-exclusions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-cloud-logging/openapi/google-cloud-logging-exclusions-api-openapi.yml
- filename: google-cloud-logging-sinks-api-openapi.yml
  format: yaml
  label: Google Cloud Logging Sinks API
  slug: google-cloud-logging-sinks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-cloud-logging/openapi/google-cloud-logging-sinks-api-openapi.yml
- filename: google-cloud-logging-entries-api-openapi.yml
  format: yaml
  label: Google Cloud Logging Cloud Logging Entries API
  slug: google-cloud-logging-entries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-cloud-logging/openapi/google-cloud-logging-entries-api-openapi.yml
- filename: google-cloud-logging-folders-api-openapi.yml
  format: yaml
  label: Google Cloud Logging Cloud Logging Folders API
  slug: google-cloud-logging-folders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-cloud-logging/openapi/google-cloud-logging-folders-api-openapi.yml
- filename: google-cloud-logging-locations-api-openapi.yml
  format: yaml
  label: Google Cloud Logging Cloud Logging Locations API
  slug: google-cloud-logging-locations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-cloud-logging/openapi/google-cloud-logging-locations-api-openapi.yml
- filename: google-cloud-logging-logs-api-openapi.yml
  format: yaml
  label: Google Cloud Logging Cloud Logging Logs API
  slug: google-cloud-logging-logs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-cloud-logging/openapi/google-cloud-logging-logs-api-openapi.yml
- filename: google-cloud-logging-organizations-api-openapi.yml
  format: yaml
  label: Google Cloud Logging Cloud Logging Organizations API
  slug: google-cloud-logging-organizations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-cloud-logging/openapi/google-cloud-logging-organizations-api-openapi.yml
- filename: google-cloud-logging-projects-api-openapi.yml
  format: yaml
  label: Google Cloud Logging Cloud Logging Projects API
  slug: google-cloud-logging-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-cloud-logging/openapi/google-cloud-logging-projects-api-openapi.yml
- filename: google-cloud-logging-billingaccounts-api-openapi.yml
  format: yaml
  label: Google Cloud Logging Billing Accounts API
  slug: google-cloud-logging-billingaccounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-cloud-logging/openapi/google-cloud-logging-billingaccounts-api-openapi.yml
- filename: google-cloud-logging-cmeksettings-api-openapi.yml
  format: yaml
  label: Google Cloud Logging Cmek Settings API
  slug: google-cloud-logging-cmeksettings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-cloud-logging/openapi/google-cloud-logging-cmeksettings-api-openapi.yml
- filename: google-cloud-logging-monitoredresourcedescriptors-api-openapi.yml
  format: yaml
  label: Google Cloud Logging Monitored Resource Descriptors API
  slug: google-cloud-logging-monitoredresourcedescriptors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-cloud-logging/openapi/google-cloud-logging-monitoredresourcedescriptors-api-openapi.yml
- filename: google-cloud-logging-settings-api-openapi.yml
  format: yaml
  label: Google Cloud Logging Settings API
  slug: google-cloud-logging-settings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-cloud-logging/openapi/google-cloud-logging-settings-api-openapi.yml
claim_count: 4
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
  - summary: High Risk Activities
    text: access or use the Services or any AI Agent (i) for High Risk Activities
  - summary: ITAR-controlled materials
    text: for materials or activities that are subject to the International Traffic in Arms Regulations (ITAR) maintained by the United States Department of State
  - summary: HIPAA health information
    text: to transmit, store, or process health information subject to United States HIPAA regulations except as permitted by an executed HIPAA BAA
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Customer must have an Account to use the Services and is responsible for the information it provides to create the Account
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Google Cloud Logging
provenance_date: '2026-11-09'
provider_name: Google Cloud Logging
provider_slug: google-cloud-logging
slug: google-cloud-logging-eligibility
source_date: '2026-11-09'
source_filename: google-cloud-logging-eligibility.yml
source_heading: Eligibility
source_page: https://cloud.google.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Google Cloud Logging\naid: google-cloud-logging\nurl: https://cloud.google.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: High Risk Activities\n  text: access or use the Services or any AI Agent (i) for High Risk Activities\n- summary: ITAR-controlled materials\n  text: for materials or activities that are subject to the International Traffic in Arms Regulations (ITAR) maintained\n    by the United States Department of State\n- summary: HIPAA health information\n  text: to transmit, store, or process\
  \ health information subject to United States HIPAA regulations except as permitted\n    by an executed HIPAA BAA\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Customer must have an Account to use the Services and is responsible for the information it provides to\n    create the Account\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/google-cloud-logging/eligibility/google-cloud-logging-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 4 quoted statements, read from Google Cloud Logging's own page on 2026-11-09.
synthetic: false
tags:
- Cloud
- Logging
- Monitoring
- Observability
- Telemetry
- Log Management
- SRE
- DevOps
- OpenTelemetry
- Google Cloud
---
