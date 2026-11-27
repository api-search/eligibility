---
api_specs:
- filename: cledara-applications-api-openapi.yml
  format: yaml
  label: Cledara Applications API
  slug: cledara-applications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cledara/openapi/cledara-applications-api-openapi.yml
- filename: cledara-transactions-api-openapi.yml
  format: yaml
  label: Cledara Transactions API
  slug: cledara-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cledara/openapi/cledara-transactions-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    - GB
    text: 'For Customers located in the United Kingdom: The ''SERVICES TERMS AND CONDITIONS'' and ''Modulr Introduced Clients Terms of Business'' applies to all Customers and Users of Cledara located in the UK.'
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
name: Cledara
provenance_date: '2026-11-09'
provider_name: Cledara
provider_slug: cledara
slug: cledara-eligibility
source_date: '2026-11-09'
source_filename: cledara-eligibility.yml
source_heading: Eligibility
source_page: https://www.cledara.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cledara\naid: cledara\nurl: https://www.cledara.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  - GB\n  excluded: []\n  text: 'For Customers located in the United Kingdom: The ''SERVICES TERMS AND CONDITIONS'' and ''Modulr Introduced\n    Clients Terms of Business'' applies to all Customers and Users of Cledara located in the UK.'\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/cledara/eligibility/cledara-eligibility.yml
stated_fields:
- countries
summary_line: 1 quoted statement, read from Cledara's own page on 2026-11-09.
synthetic: false
tags:
- Finance
- SaaS Management
- Software Spending
- Spend Management
- Subscription Management
- Virtual Cards
- Expense Management
- FinOps
- MCP
- Market Data
---
