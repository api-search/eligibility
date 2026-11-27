---
api_specs:
- filename: chase-rewards-balance-api-openapi.yml
  format: yaml
  label: Chase Rewards Balance API
  slug: rewards-balance-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chase/openapi/chase-rewards-balance-api-openapi.yml
- filename: chase-accounts-api-openapi.yml
  format: yaml
  label: Chase Accounts API
  slug: chase-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chase/openapi/chase-accounts-api-openapi.yml
- filename: chase-consents-api-openapi.yml
  format: yaml
  label: Chase Consents API
  slug: chase-consents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chase/openapi/chase-consents-api-openapi.yml
- filename: chase-customers-api-openapi.yml
  format: yaml
  label: Chase Customers API
  slug: chase-customers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chase/openapi/chase-customers-api-openapi.yml
- filename: chase-enrollments-api-openapi.yml
  format: yaml
  label: Chase Enrollments API
  slug: chase-enrollments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chase/openapi/chase-enrollments-api-openapi.yml
- filename: chase-merchants-api-openapi.yml
  format: yaml
  label: Chase Merchants API
  slug: chase-merchants-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chase/openapi/chase-merchants-api-openapi.yml
- filename: chase-orders-api-openapi.yml
  format: yaml
  label: Chase Orders API
  slug: chase-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chase/openapi/chase-orders-api-openapi.yml
- filename: chase-refunds-api-openapi.yml
  format: yaml
  label: Chase Refunds API
  slug: chase-refunds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chase/openapi/chase-refunds-api-openapi.yml
- filename: chase-statements-api-openapi.yml
  format: yaml
  label: Chase Statements API
  slug: chase-statements-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chase/openapi/chase-statements-api-openapi.yml
- filename: chase-tax-forms-api-openapi.yml
  format: yaml
  label: Chase Tax Forms API
  slug: chase-tax-forms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chase/openapi/chase-tax-forms-api-openapi.yml
- filename: chase-transactions-api-openapi.yml
  format: yaml
  label: Chase Transactions API
  slug: chase-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chase/openapi/chase-transactions-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Services are not intended for distribution to, or use by, any person or entity in any jurisdiction or country where such distribution or use would be contrary to local law or regulation or where Chase has not approved its distribution.
  entity_types:
  - text: '"Client Developer" means a software developer, software developing entity, service provider, or other qualified entity or customer invited to and authorized to access the Portal.'
    type: developer
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Competing with Chase
    text: will not use the Portal or any of the Services to compete with Chase or for the benefit of any competitor of Chase
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
name: Chase
provenance_date: '2026-11-09'
provider_name: Chase
provider_slug: chase
slug: chase-eligibility
source_date: '2026-11-09'
source_filename: chase-eligibility.yml
source_heading: Eligibility
source_page: https://developer.chase.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Chase\naid: chase\nurl: https://developer.chase.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Services are not intended for distribution to, or use by, any person or entity in any jurisdiction or\n    country where such distribution or use would be contrary to local law or regulation or where Chase has not approved\n    its distribution.\nentity_types:\n- type: developer\n  text: '\"Client Developer\" means a software developer, software developing entity, service provider, or other qualified\n    entity or customer invited to and authorized to access the Portal.'\n\
  restricted_uses:\n- summary: Competing with Chase\n  text: will not use the Portal or any of the Services to compete with Chase or for the benefit of any competitor\n    of Chase\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/chase/eligibility/chase-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Chase's own page on 2026-11-09.
synthetic: false
tags:
- Account Aggregation
- Banking
- Consent
- Credit Cards
- FDX
- Financial Services
- Loyalty
- Open Banking
- Pay with Points
- Rewards
- Consumer Banking
---
