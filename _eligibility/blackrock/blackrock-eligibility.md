---
api_specs:
- filename: blackrock-authorizationurl-generate-api-openapi.yml
  format: yaml
  label: BlackRock Authorization Url:generate API
  slug: blackrock-authorizationurl-generate-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blackrock/openapi/blackrock-authorizationurl-generate-api-openapi.yml
- filename: blackrock-studionotifications-api-openapi.yml
  format: yaml
  label: BlackRock Studio Notifications API
  slug: blackrock-studionotifications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blackrock/openapi/blackrock-studionotifications-api-openapi.yml
- filename: blackrock-studionotifications-batchcreate-api-openapi.yml
  format: yaml
  label: BlackRock Studio Notifications:batch Create API
  slug: blackrock-studionotifications-batchcreate-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blackrock/openapi/blackrock-studionotifications-batchcreate-api-openapi.yml
- filename: blackrock-studionotifications-filter-api-openapi.yml
  format: yaml
  label: BlackRock Studio Notifications:filter API
  slug: blackrock-studionotifications-filter-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blackrock/openapi/blackrock-studionotifications-filter-api-openapi.yml
- filename: blackrock-studiosubscriptions-api-openapi.yml
  format: yaml
  label: BlackRock Studio Subscriptions API
  slug: blackrock-studiosubscriptions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blackrock/openapi/blackrock-studiosubscriptions-api-openapi.yml
- filename: blackrock-studiosubscriptions-batchcreate-api-openapi.yml
  format: yaml
  label: BlackRock Studio Subscriptions:batch Create API
  slug: blackrock-studiosubscriptions-batchcreate-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blackrock/openapi/blackrock-studiosubscriptions-batchcreate-api-openapi.yml
- filename: blackrock-studiosubscriptions-filter-api-openapi.yml
  format: yaml
  label: BlackRock Studio Subscriptions:filter API
  slug: blackrock-studiosubscriptions-filter-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blackrock/openapi/blackrock-studiosubscriptions-filter-api-openapi.yml
- filename: blackrock-token-checktokenexists-api-openapi.yml
  format: yaml
  label: BlackRock Token:check Token Exists API
  slug: blackrock-token-checktokenexists-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blackrock/openapi/blackrock-token-checktokenexists-api-openapi.yml
- filename: blackrock-token-generate-api-openapi.yml
  format: yaml
  label: BlackRock Token:generate API
  slug: blackrock-token-generate-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blackrock/openapi/blackrock-token-generate-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Each investment product and service referred to on this Website is intended to be made available to only U.S. residents.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Investment solicitation restrictions
    text: The information provided on this Website is not intended for distribution to, or use by, any person or entity in any jurisdiction or country where such distribution or use would be contrary to law or regulation
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
name: BlackRock
provenance_date: '2026-11-09'
provider_name: BlackRock
provider_slug: blackrock
slug: blackrock-eligibility
source_date: '2026-11-09'
source_filename: blackrock-eligibility.yml
source_heading: Eligibility
source_page: https://www.blackrock.com/corporate/compliance/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BlackRock\naid: blackrock\nurl: https://www.blackrock.com/corporate/compliance/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Each investment product and service referred to on this Website is intended to be made available to only\n    U.S. residents.\nentity_types: []\nrestricted_uses:\n- summary: Investment solicitation restrictions\n  text: The information provided on this Website is not intended for distribution to, or use by, any person or entity\n    in any jurisdiction or country where such distribution or use would be contrary to law or regulation\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/blackrock/eligibility/blackrock-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from BlackRock's own page on 2026-11-09.
synthetic: false
tags:
- Asset Management
- Finance
- Fintech
- Investment Management
- Portfolio Management
- Risk Analytics
- Fortune 500
---
