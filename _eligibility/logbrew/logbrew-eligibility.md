---
api_specs:
- filename: logbrew-account-api-openapi.yml
  format: yaml
  label: LogBrew Account API
  slug: logbrew-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/logbrew/openapi/logbrew-account-api-openapi.yml
- filename: logbrew-actions-api-openapi.yml
  format: yaml
  label: LogBrew Actions API
  slug: logbrew-actions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/logbrew/openapi/logbrew-actions-api-openapi.yml
- filename: logbrew-alerts-api-openapi.yml
  format: yaml
  label: LogBrew Alerts API
  slug: logbrew-alerts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/logbrew/openapi/logbrew-alerts-api-openapi.yml
- filename: logbrew-billing-api-openapi.yml
  format: yaml
  label: LogBrew Billing API
  slug: logbrew-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/logbrew/openapi/logbrew-billing-api-openapi.yml
- filename: logbrew-connected-clients-api-openapi.yml
  format: yaml
  label: LogBrew Connected clients API
  slug: logbrew-connected-clients-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/logbrew/openapi/logbrew-connected-clients-api-openapi.yml
- filename: logbrew-debug-files-api-openapi.yml
  format: yaml
  label: LogBrew Debug files API
  slug: logbrew-debug-files-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/logbrew/openapi/logbrew-debug-files-api-openapi.yml
- filename: logbrew-ingestion-api-openapi.yml
  format: yaml
  label: LogBrew Ingestion API
  slug: logbrew-ingestion-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/logbrew/openapi/logbrew-ingestion-api-openapi.yml
- filename: logbrew-issues-api-openapi.yml
  format: yaml
  label: LogBrew Issues API
  slug: logbrew-issues-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/logbrew/openapi/logbrew-issues-api-openapi.yml
- filename: logbrew-live-feed-api-openapi.yml
  format: yaml
  label: LogBrew Live feed API
  slug: logbrew-live-feed-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/logbrew/openapi/logbrew-live-feed-api-openapi.yml
- filename: logbrew-logs-api-openapi.yml
  format: yaml
  label: LogBrew Logs API
  slug: logbrew-logs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/logbrew/openapi/logbrew-logs-api-openapi.yml
- filename: logbrew-metrics-api-openapi.yml
  format: yaml
  label: LogBrew Metrics API
  slug: logbrew-metrics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/logbrew/openapi/logbrew-metrics-api-openapi.yml
- filename: logbrew-organizations-api-openapi.yml
  format: yaml
  label: LogBrew Organizations API
  slug: logbrew-organizations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/logbrew/openapi/logbrew-organizations-api-openapi.yml
- filename: logbrew-product-analytics-api-openapi.yml
  format: yaml
  label: LogBrew Product analytics API
  slug: logbrew-product-analytics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/logbrew/openapi/logbrew-product-analytics-api-openapi.yml
- filename: logbrew-projects-api-openapi.yml
  format: yaml
  label: LogBrew Projects API
  slug: logbrew-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/logbrew/openapi/logbrew-projects-api-openapi.yml
- filename: logbrew-releases-api-openapi.yml
  format: yaml
  label: LogBrew Releases API
  slug: logbrew-releases-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/logbrew/openapi/logbrew-releases-api-openapi.yml
- filename: logbrew-support-api-openapi.yml
  format: yaml
  label: LogBrew Support API
  slug: logbrew-support-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/logbrew/openapi/logbrew-support-api-openapi.yml
- filename: logbrew-traces-api-openapi.yml
  format: yaml
  label: LogBrew Traces API
  slug: logbrew-traces-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/logbrew/openapi/logbrew-traces-api-openapi.yml
- filename: logbrew-volume-api-openapi.yml
  format: yaml
  label: LogBrew Volume API
  slug: logbrew-volume-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/logbrew/openapi/logbrew-volume-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be legally able to enter this agreement.
    type: individual
  - text: If you use LogBrew for an organization, you confirm that you have authority to bind it.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Protected health information
    text: Do not send protected health information. LogBrew does not sign business associate agreements (BAAs).
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
name: LogBrew
provenance_date: '2026-11-09'
provider_name: LogBrew
provider_slug: logbrew
slug: logbrew-eligibility
source_date: '2026-11-09'
source_filename: logbrew-eligibility.yml
source_heading: Eligibility
source_page: https://logbrew.co/en/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: LogBrew\naid: logbrew\nurl: https://logbrew.co/en/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be legally able to enter this agreement.\n- type: business\n  text: If you use LogBrew for an organization, you confirm that you have authority to bind it.\nrestricted_uses:\n- summary: Protected health information\n  text: Do not send protected health information. LogBrew does not sign business associate agreements (BAAs).\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/logbrew/eligibility/logbrew-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from LogBrew's own page on 2026-11-09.
synthetic: false
tags:
- Observability
- Logging
- Monitoring
- Analytics
- Error Tracking
---
