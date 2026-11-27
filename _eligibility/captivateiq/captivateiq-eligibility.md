---
api_specs:
- filename: captivateiq-attribute-worksheets-api-openapi.yml
  format: yaml
  label: CaptivateIQ Attribute Worksheets API
  slug: captivateiq-attribute-worksheets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/captivateiq/openapi/captivateiq-attribute-worksheets-api-openapi.yml
- filename: captivateiq-audit-logs-api-openapi.yml
  format: yaml
  label: CaptivateIQ Audit Logs API
  slug: captivateiq-audit-logs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/captivateiq/openapi/captivateiq-audit-logs-api-openapi.yml
- filename: captivateiq-commission-plans-api-openapi.yml
  format: yaml
  label: CaptivateIQ Commission Plans API
  slug: captivateiq-commission-plans-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/captivateiq/openapi/captivateiq-commission-plans-api-openapi.yml
- filename: captivateiq-dashboards-api-openapi.yml
  format: yaml
  label: CaptivateIQ Dashboards API
  slug: captivateiq-dashboards-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/captivateiq/openapi/captivateiq-dashboards-api-openapi.yml
- filename: captivateiq-data-workbooks-api-openapi.yml
  format: yaml
  label: CaptivateIQ Data Workbooks API
  slug: captivateiq-data-workbooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/captivateiq/openapi/captivateiq-data-workbooks-api-openapi.yml
- filename: captivateiq-data-worksheets-api-openapi.yml
  format: yaml
  label: CaptivateIQ Data Worksheets API
  slug: captivateiq-data-worksheets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/captivateiq/openapi/captivateiq-data-worksheets-api-openapi.yml
- filename: captivateiq-employee-assumptions-api-openapi.yml
  format: yaml
  label: CaptivateIQ Employee Assumptions API
  slug: captivateiq-employee-assumptions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/captivateiq/openapi/captivateiq-employee-assumptions-api-openapi.yml
- filename: captivateiq-employees-api-openapi.yml
  format: yaml
  label: CaptivateIQ Employees API
  slug: captivateiq-employees-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/captivateiq/openapi/captivateiq-employees-api-openapi.yml
- filename: captivateiq-hierarchies-api-openapi.yml
  format: yaml
  label: CaptivateIQ Hierarchies API
  slug: captivateiq-hierarchies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/captivateiq/openapi/captivateiq-hierarchies-api-openapi.yml
- filename: captivateiq-jobs-api-openapi.yml
  format: yaml
  label: CaptivateIQ Jobs API
  slug: captivateiq-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/captivateiq/openapi/captivateiq-jobs-api-openapi.yml
- filename: captivateiq-metadata-api-openapi.yml
  format: yaml
  label: CaptivateIQ Metadata API
  slug: captivateiq-metadata-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/captivateiq/openapi/captivateiq-metadata-api-openapi.yml
- filename: captivateiq-payouts-api-openapi.yml
  format: yaml
  label: CaptivateIQ Payouts API
  slug: captivateiq-payouts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/captivateiq/openapi/captivateiq-payouts-api-openapi.yml
- filename: captivateiq-report-models-api-openapi.yml
  format: yaml
  label: CaptivateIQ Report Models API
  slug: captivateiq-report-models-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/captivateiq/openapi/captivateiq-report-models-api-openapi.yml
- filename: captivateiq-transformation-worksheets-api-openapi.yml
  format: yaml
  label: CaptivateIQ Transformation Worksheets API
  slug: captivateiq-transformation-worksheets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/captivateiq/openapi/captivateiq-transformation-worksheets-api-openapi.yml
- filename: captivateiq-uploads-api-openapi.yml
  format: yaml
  label: CaptivateIQ Uploads API
  slug: captivateiq-uploads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/captivateiq/openapi/captivateiq-uploads-api-openapi.yml
- filename: captivateiq-users-api-openapi.yml
  format: yaml
  label: CaptivateIQ Users API
  slug: captivateiq-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/captivateiq/openapi/captivateiq-users-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Customer agrees to these API Terms on behalf of the company or other legal entity for which Customer is accepting these API Terms
    type: business
  minimum_age:
    text: null
    value: null
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
name: CaptivateIQ
provenance_date: '2026-11-09'
provider_name: CaptivateIQ
provider_slug: captivateiq
slug: captivateiq-eligibility
source_date: '2026-11-09'
source_filename: captivateiq-eligibility.yml
source_heading: Eligibility
source_page: https://developers.captivateiq.com/page/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CaptivateIQ\naid: captivateiq\nurl: https://developers.captivateiq.com/page/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Customer agrees to these API Terms on behalf of the company or other legal entity for which Customer is\n    accepting these API Terms\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/captivateiq/eligibility/captivateiq-eligibility.yml
stated_fields:
- entity_types
summary_line: 1 quoted statement, read from CaptivateIQ's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Cloud Saas
- Sales Commissions
- Incentive Compensation Management
- Sales Performance Management
- Revenue Operations
- Finance
- Payouts
- Commission Plans
- Sales Compensation
---
