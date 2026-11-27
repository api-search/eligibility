---
api_specs:
- filename: ai2fin-com-ai-analysis-api-openapi.yml
  format: yaml
  label: AI2Fin AI Analysis API
  slug: ai2fin-com-ai-analysis-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ai2fin-com/openapi/ai2fin-com-ai-analysis-api-openapi.yml
- filename: ai2fin-com-ai-assistant-api-openapi.yml
  format: yaml
  label: AI2Fin AI Assistant API
  slug: ai2fin-com-ai-assistant-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ai2fin-com/openapi/ai2fin-com-ai-assistant-api-openapi.yml
- filename: ai2fin-com-ai-services-api-openapi.yml
  format: yaml
  label: AI2Fin AI Services API
  slug: ai2fin-com-ai-services-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ai2fin-com/openapi/ai2fin-com-ai-services-api-openapi.yml
- filename: ai2fin-com-analytics-reports-api-openapi.yml
  format: yaml
  label: AI2Fin Analytics & Reports API
  slug: ai2fin-com-analytics-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ai2fin-com/openapi/ai2fin-com-analytics-reports-api-openapi.yml
- filename: ai2fin-com-authentication-api-openapi.yml
  format: yaml
  label: AI2Fin Authentication API
  slug: ai2fin-com-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ai2fin-com/openapi/ai2fin-com-authentication-api-openapi.yml
- filename: ai2fin-com-automation-api-openapi.yml
  format: yaml
  label: AI2Fin Automation API
  slug: ai2fin-com-automation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ai2fin-com/openapi/ai2fin-com-automation-api-openapi.yml
- filename: ai2fin-com-bank-transactions-api-openapi.yml
  format: yaml
  label: AI2Fin Bank Transactions API
  slug: ai2fin-com-bank-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ai2fin-com/openapi/ai2fin-com-bank-transactions-api-openapi.yml
- filename: ai2fin-com-bills-recurring-payments-api-openapi.yml
  format: yaml
  label: AI2Fin Bills & Recurring Payments API
  slug: ai2fin-com-bills-recurring-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ai2fin-com/openapi/ai2fin-com-bills-recurring-payments-api-openapi.yml
- filename: ai2fin-com-categories-api-openapi.yml
  format: yaml
  label: AI2Fin Categories API
  slug: ai2fin-com-categories-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ai2fin-com/openapi/ai2fin-com-categories-api-openapi.yml
- filename: ai2fin-com-expenses-api-openapi.yml
  format: yaml
  label: AI2Fin Expenses API
  slug: ai2fin-com-expenses-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ai2fin-com/openapi/ai2fin-com-expenses-api-openapi.yml
- filename: ai2fin-com-gst-tax-api-openapi.yml
  format: yaml
  label: AI2Fin GST & Tax API
  slug: ai2fin-com-gst-tax-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ai2fin-com/openapi/ai2fin-com-gst-tax-api-openapi.yml
- filename: ai2fin-com-mcp-server-api-openapi.yml
  format: yaml
  label: AI2Fin MCP Server API
  slug: ai2fin-com-mcp-server-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ai2fin-com/openapi/ai2fin-com-mcp-server-api-openapi.yml
- filename: ai2fin-com-receipts-attachments-api-openapi.yml
  format: yaml
  label: AI2Fin Receipts & Attachments API
  slug: ai2fin-com-receipts-attachments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ai2fin-com/openapi/ai2fin-com-receipts-attachments-api-openapi.yml
- filename: ai2fin-com-search-api-openapi.yml
  format: yaml
  label: AI2Fin Search API
  slug: ai2fin-com-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ai2fin-com/openapi/ai2fin-com-search-api-openapi.yml
- filename: ai2fin-com-smart-categories-api-openapi.yml
  format: yaml
  label: AI2Fin Smart Categories API
  slug: ai2fin-com-smart-categories-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ai2fin-com/openapi/ai2fin-com-smart-categories-api-openapi.yml
- filename: ai2fin-com-subscription-api-openapi.yml
  format: yaml
  label: AI2Fin Subscription API
  slug: ai2fin-com-subscription-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ai2fin-com/openapi/ai2fin-com-subscription-api-openapi.yml
- filename: ai2fin-com-travel-vehicles-api-openapi.yml
  format: yaml
  label: AI2Fin Travel & Vehicles API
  slug: ai2fin-com-travel-vehicles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ai2fin-com/openapi/ai2fin-com-travel-vehicles-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - AU
    text: 'Jurisdiction: Australia'
  entity_types:
  - text: Use only one account per individual or business
    type: individual
  - text: Use only one account per individual or business
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Lawful purposes only
    text: Use the service only for lawful purposes
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
name: AI2Fin
provenance_date: '2026-11-09'
provider_name: AI2Fin
provider_slug: ai2fin-com
slug: ai2fin-com-eligibility
source_date: '2026-11-09'
source_filename: ai2fin-com-eligibility.yml
source_heading: Eligibility
source_page: https://app.ai2fin.com/#/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AI2Fin\naid: ai2fin-com\nurl: https://app.ai2fin.com/#/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - AU\n  excluded: []\n  text: 'Jurisdiction: Australia'\nentity_types:\n- type: individual\n  text: Use only one account per individual or business\n- type: business\n  text: Use only one account per individual or business\nrestricted_uses:\n- summary: Lawful purposes only\n  text: Use the service only for lawful purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/ai2fin-com/eligibility/ai2fin-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from AI2Fin's own page on 2026-11-09.
synthetic: false
tags:
- Finance
- Tax
- Personal Finance
- Software-as-a-Service
- Employee Benefits
---
