---
api_specs:
- filename: useagentbank-payouts-api-openapi.yml
  format: yaml
  label: AgentBank Payouts API
  slug: useagentbank-payouts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/useagentbank/openapi/useagentbank-payouts-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Access to a particular currency, country, payment method, or provider is subject to availability and applicable eligibility requirements.
  entity_types:
  - text: You must be legally able to enter into an agreement and use the requested service.
    type: individual
  - text: If you use the service on behalf of a business, you must have authority to act for that business and to give the instructions you submit.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Fraud, false information, sanctions evasion
    text: You must not submit false identity or recipient information, use stolen credentials, facilitate fraud or money laundering, evade applicable sanctions, or interfere with the security of the service.
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
name: AgentBank
provenance_date: '2026-11-10'
provider_name: AgentBank
provider_slug: useagentbank
slug: useagentbank-eligibility
source_date: '2026-11-10'
source_filename: useagentbank-eligibility.yml
source_heading: Eligibility
source_page: https://useagentbank.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AgentBank\naid: useagentbank\nurl: https://useagentbank.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Access to a particular currency, country, payment method, or provider is subject to availability and applicable\n    eligibility requirements.\nentity_types:\n- type: individual\n  text: You must be legally able to enter into an agreement and use the requested service.\n- type: business\n  text: If you use the service on behalf of a business, you must have authority to act for that business and to\n    give the instructions you submit.\nrestricted_uses:\n- summary: Fraud,\
  \ false information, sanctions evasion\n  text: You must not submit false identity or recipient information, use stolen credentials, facilitate fraud or\n    money laundering, evade applicable sanctions, or interfere with the security of the service.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/useagentbank/eligibility/useagentbank-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from AgentBank's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Finance
- Artificial Intelligence
- Banking
- Cryptocurrency
- Payments
---
