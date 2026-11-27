---
api_specs:
- filename: financialfilings-com-openapi.yml
  format: yaml
  label: Financial Filings API
  slug: financial-filings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/financialfilings-com/openapi/financialfilings-com-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: whether personally or on behalf of an entity ("you" or "User")
    type: individual
  - text: on behalf of an entity
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Academic publications
    text: Using the Data, or any result derived from it, in an academic or scholarly publication requires a separate written academic or enterprise license from us.
  - summary: Competing product
    text: (b) using the Service to develop a competing product
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
name: FinancialFilings
provenance_date: '2026-11-09'
provider_name: FinancialFilings
provider_slug: financialfilings-com
slug: financialfilings-com-eligibility
source_date: '2026-11-09'
source_filename: financialfilings-com-eligibility.yml
source_heading: Eligibility
source_page: https://financialfilings.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: FinancialFilings\naid: financialfilings-com\nurl: https://financialfilings.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: whether personally or on behalf of an entity (\"you\" or \"User\")\n- type: business\n  text: on behalf of an entity\nrestricted_uses:\n- summary: Academic publications\n  text: Using the Data, or any result derived from it, in an academic or scholarly publication requires a separate\n    written academic or enterprise license from us.\n- summary: Competing product\n  text: (b) using the Service to develop\
  \ a competing product\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/financialfilings-com/eligibility/financialfilings-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from FinancialFilings's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Financial Data
- Filings
- Market Data
- Research
---
