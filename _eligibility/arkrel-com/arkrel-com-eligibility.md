---
api_specs:
- filename: arkrel-com-account-data-api-openapi.yml
  format: yaml
  label: Conecta Media LLC Account Data API
  slug: arkrel-com-account-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arkrel-com/openapi/arkrel-com-account-data-api-openapi.yml
- filename: arkrel-com-auth-api-openapi.yml
  format: yaml
  label: Conecta Media LLC Auth API
  slug: arkrel-com-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arkrel-com/openapi/arkrel-com-auth-api-openapi.yml
- filename: arkrel-com-billing-api-openapi.yml
  format: yaml
  label: Conecta Media LLC Billing API
  slug: arkrel-com-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arkrel-com/openapi/arkrel-com-billing-api-openapi.yml
- filename: arkrel-com-businesses-api-openapi.yml
  format: yaml
  label: Conecta Media LLC Businesses API
  slug: arkrel-com-businesses-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arkrel-com/openapi/arkrel-com-businesses-api-openapi.yml
- filename: arkrel-com-category-rules-api-openapi.yml
  format: yaml
  label: Conecta Media LLC Category Rules API
  slug: arkrel-com-category-rules-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arkrel-com/openapi/arkrel-com-category-rules-api-openapi.yml
- filename: arkrel-com-chart-of-accounts-api-openapi.yml
  format: yaml
  label: Conecta Media LLC Chart Of Accounts API
  slug: arkrel-com-chart-of-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arkrel-com/openapi/arkrel-com-chart-of-accounts-api-openapi.yml
- filename: arkrel-com-connections-api-openapi.yml
  format: yaml
  label: Conecta Media LLC Connections API
  slug: arkrel-com-connections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arkrel-com/openapi/arkrel-com-connections-api-openapi.yml
- filename: arkrel-com-documents-api-openapi.yml
  format: yaml
  label: Conecta Media LLC Documents API
  slug: arkrel-com-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arkrel-com/openapi/arkrel-com-documents-api-openapi.yml
- filename: arkrel-com-mcp-api-openapi.yml
  format: yaml
  label: Conecta Media LLC MCP API
  slug: arkrel-com-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arkrel-com/openapi/arkrel-com-mcp-api-openapi.yml
- filename: arkrel-com-ops-api-openapi.yml
  format: yaml
  label: Conecta Media LLC Ops API
  slug: arkrel-com-ops-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arkrel-com/openapi/arkrel-com-ops-api-openapi.yml
- filename: arkrel-com-schemas-api-openapi.yml
  format: yaml
  label: Conecta Media LLC Schemas API
  slug: arkrel-com-schemas-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arkrel-com/openapi/arkrel-com-schemas-api-openapi.yml
- filename: arkrel-com-settings-api-openapi.yml
  format: yaml
  label: Conecta Media LLC Settings API
  slug: arkrel-com-settings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arkrel-com/openapi/arkrel-com-settings-api-openapi.yml
- filename: arkrel-com-statement-sets-api-openapi.yml
  format: yaml
  label: Conecta Media LLC Statement Sets API
  slug: arkrel-com-statement-sets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arkrel-com/openapi/arkrel-com-statement-sets-api-openapi.yml
- filename: arkrel-com-tax-report-api-openapi.yml
  format: yaml
  label: Conecta Media LLC Tax Report API
  slug: arkrel-com-tax-report-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arkrel-com/openapi/arkrel-com-tax-report-api-openapi.yml
- filename: arkrel-com-tax-years-api-openapi.yml
  format: yaml
  label: Conecta Media LLC Tax Years API
  slug: arkrel-com-tax-years-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arkrel-com/openapi/arkrel-com-tax-years-api-openapi.yml
- filename: arkrel-com-usage-api-openapi.yml
  format: yaml
  label: Conecta Media LLC Usage API
  slug: arkrel-com-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arkrel-com/openapi/arkrel-com-usage-api-openapi.yml
- filename: arkrel-com-webhooks-api-openapi.yml
  format: yaml
  label: Conecta Media LLC Webhooks API
  slug: arkrel-com-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arkrel-com/openapi/arkrel-com-webhooks-api-openapi.yml
- filename: arkrel-com-year-overview-api-openapi.yml
  format: yaml
  label: Conecta Media LLC Year Overview API
  slug: arkrel-com-year-overview-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arkrel-com/openapi/arkrel-com-year-overview-api-openapi.yml
claim_count: 1
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
  - summary: No PHI or medical records
    text: You will not use the Service to process protected health information (PHI) or other medical records
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
name: Conecta Media LLC
provenance_date: '2026-11-09'
provider_name: Conecta Media LLC
provider_slug: arkrel-com
slug: arkrel-com-eligibility
source_date: '2026-11-09'
source_filename: arkrel-com-eligibility.yml
source_heading: Eligibility
source_page: https://arkrel.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Conecta Media LLC\naid: arkrel-com\nurl: https://arkrel.com/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: No PHI or medical records\n  text: You will not use the Service to process protected health information (PHI) or other medical records\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/arkrel-com/eligibility/arkrel-com-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Conecta Media LLC's own page on 2026-11-09.
synthetic: false
tags:
- Finance
- Bookkeeping
- Tax
- Software-as-a-Service
- Self-Employed
---
