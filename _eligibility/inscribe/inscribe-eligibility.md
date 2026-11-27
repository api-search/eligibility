---
api_specs:
- filename: inscribe-bank-accounts-api-openapi.yml
  format: yaml
  label: Inscribe Bank Accounts API
  slug: inscribe-bank-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/inscribe/openapi/inscribe-bank-accounts-api-openapi.yml
- filename: inscribe-collect-sessions-api-openapi.yml
  format: yaml
  label: Inscribe Collect Sessions API
  slug: inscribe-collect-sessions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/inscribe/openapi/inscribe-collect-sessions-api-openapi.yml
- filename: inscribe-credit-insights-api-openapi.yml
  format: yaml
  label: Inscribe Credit Insights API
  slug: inscribe-credit-insights-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/inscribe/openapi/inscribe-credit-insights-api-openapi.yml
- filename: inscribe-customers-api-openapi.yml
  format: yaml
  label: Inscribe Customers API
  slug: inscribe-customers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/inscribe/openapi/inscribe-customers-api-openapi.yml
- filename: inscribe-documents-api-openapi.yml
  format: yaml
  label: Inscribe Documents API
  slug: inscribe-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/inscribe/openapi/inscribe-documents-api-openapi.yml
- filename: inscribe-open-banking-api-openapi.yml
  format: yaml
  label: Inscribe Open Banking API
  slug: inscribe-open-banking-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/inscribe/openapi/inscribe-open-banking-api-openapi.yml
- filename: inscribe-reachability-check-api-openapi.yml
  format: yaml
  label: Inscribe Reachability Check API
  slug: inscribe-reachability-check-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/inscribe/openapi/inscribe-reachability-check-api-openapi.yml
- filename: inscribe-transactions-api-openapi.yml
  format: yaml
  label: Inscribe Transactions API
  slug: inscribe-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/inscribe/openapi/inscribe-transactions-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are entering into this Agreement on behalf of a Customer that is a company or other legal entity, you warrant and represent that you have the authority to bind such entity
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Fraud screening use only
    text: Where Customer uses the Fraud Detection Service, Customer may only use the Output for fraud screening and detection purposes.
  - summary: No government eligibility or FCRA consumer report use
    text: Customer shall not use this Service (i) to determine eligibility for any government license, benefit or assistance
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
name: Inscribe
provenance_date: '2026-11-09'
provider_name: Inscribe
provider_slug: inscribe
slug: inscribe-eligibility
source_date: '2026-11-09'
source_filename: inscribe-eligibility.yml
source_heading: Eligibility
source_page: https://www.inscribe.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Inscribe\naid: inscribe\nurl: https://www.inscribe.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are entering into this Agreement on behalf of a Customer that is a company or other legal entity,\n    you warrant and represent that you have the authority to bind such entity\nrestricted_uses:\n- summary: Fraud screening use only\n  text: Where Customer uses the Fraud Detection Service, Customer may only use the Output for fraud screening and\n    detection purposes.\n- summary: No government eligibility or FCRA consumer\
  \ report use\n  text: Customer shall not use this Service (i) to determine eligibility for any government license, benefit or\n    assistance\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/inscribe/eligibility/inscribe-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Inscribe's own page on 2026-11-09.
synthetic: false
tags:
- Fraud Prevention
- Document Verification
- Financial Services
- KYC
- KYB
- Bank Statements
- Paystubs
- Identity Verification
- Risk Management
- Fintech
- Artificial Intelligence
- Machine Learning
---
