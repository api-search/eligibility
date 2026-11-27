---
api_specs:
- filename: zillapi-account-api-openapi.yml
  format: yaml
  label: Zillapi Account API
  slug: zillapi-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zillapi/openapi/zillapi-account-api-openapi.yml
- filename: zillapi-buildings-api-openapi.yml
  format: yaml
  label: Zillapi Buildings API
  slug: zillapi-buildings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zillapi/openapi/zillapi-buildings-api-openapi.yml
- filename: zillapi-jobs-api-openapi.yml
  format: yaml
  label: Zillapi Jobs API
  slug: zillapi-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zillapi/openapi/zillapi-jobs-api-openapi.yml
- filename: zillapi-listings-api-openapi.yml
  format: yaml
  label: Zillapi Listings API
  slug: zillapi-listings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zillapi/openapi/zillapi-listings-api-openapi.yml
- filename: zillapi-properties-api-openapi.yml
  format: yaml
  label: Zillapi Properties API
  slug: zillapi-properties-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zillapi/openapi/zillapi-properties-api-openapi.yml
- filename: zillapi-search-api-openapi.yml
  format: yaml
  label: Zillapi Search API
  slug: zillapi-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zillapi/openapi/zillapi-search-api-openapi.yml
- filename: zillapi-webhooks-api-openapi.yml
  format: yaml
  label: Zillapi Webhooks API
  slug: zillapi-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zillapi/openapi/zillapi-webhooks-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old and able to form a binding contract under the law of your jurisdiction.
    type: individual
  - text: If you use the Service on behalf of an organization, you represent that you have authority to bind that organization, and “you” refers to that organization.
    type: business
  minimum_age:
    text: You must be at least 18 years old and able to form a binding contract under the law of your jurisdiction.
    value: '18'
  restricted_uses:
  - summary: Credit, insurance, employment or housing decisions
    text: Use the Service or its data as a factor in decisions about a person’s eligibility for credit, insurance, employment or housing, or for any purpose covered by the Fair Credit Reporting Act.
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
name: Zillapi
provenance_date: '2026-11-10'
provider_name: Zillapi
provider_slug: zillapi
slug: zillapi-eligibility
source_date: '2026-11-10'
source_filename: zillapi-eligibility.yml
source_heading: Eligibility
source_page: https://zillapi.com/legal/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Zillapi\naid: zillapi\nurl: https://zillapi.com/legal/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old and able to form a binding contract under the law of your jurisdiction.\n- type: business\n  text: If you use the Service on behalf of an organization, you represent that you have authority to bind that\n    organization, and “you” refers to that organization.\nrestricted_uses:\n- summary: Credit, insurance, employment or housing decisions\n  text: Use the Service or its data as a factor in\
  \ decisions about a person’s eligibility for credit, insurance,\n    employment or housing, or for any purpose covered by the Fair Credit Reporting Act.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and able to form a binding contract under the law of your jurisdiction.\n"
source_yaml_url: https://artifacts.apis.io/zillapi/eligibility/zillapi-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Zillapi's own page on 2026-11-10.
synthetic: false
tags:
- Real Estate
- PropTech
- Property Data
- Zillow
- Zestimate
- Valuation
- AVM
- Listings
- MCP
- AI Agents
- REST API
---
