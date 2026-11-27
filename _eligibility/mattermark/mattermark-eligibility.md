---
api_specs:
- filename: mattermark-companies-api-openapi.yml
  format: yaml
  label: Mattermark Companies API
  slug: mattermark-companies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mattermark/openapi/mattermark-companies-api-openapi.yml
- filename: mattermark-complex-queries-api-openapi.yml
  format: yaml
  label: Mattermark Complex Queries API
  slug: mattermark-complex-queries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mattermark/openapi/mattermark-complex-queries-api-openapi.yml
- filename: mattermark-funding-events-api-openapi.yml
  format: yaml
  label: Mattermark Funding Events API
  slug: mattermark-funding-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mattermark/openapi/mattermark-funding-events-api-openapi.yml
- filename: mattermark-investors-api-openapi.yml
  format: yaml
  label: Mattermark Investors API
  slug: mattermark-investors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mattermark/openapi/mattermark-investors-api-openapi.yml
- filename: mattermark-search-api-openapi.yml
  format: yaml
  label: Mattermark Search API
  slug: mattermark-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mattermark/openapi/mattermark-search-api-openapi.yml
- filename: mattermark-utilities-api-openapi.yml
  format: yaml
  label: Mattermark Utilities API
  slug: mattermark-utilities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mattermark/openapi/mattermark-utilities-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You represent that you are not located in a country that is subject to a U.S. Government embargo
  entity_types:
  - text: the entity or company that you represent
    type: business
  minimum_age:
    text: you are at least 18 years of age
    value: '18'
  restricted_uses:
  - summary: Internal business use only
    text: solely for your internal business purposes
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: we alone will determine whether or not to approve your proposed account.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Mattermark
provenance_date: '2026-11-10'
provider_name: Mattermark
provider_slug: mattermark
slug: mattermark-eligibility
source_date: '2026-11-10'
source_filename: mattermark-eligibility.yml
source_heading: Eligibility
source_page: https://mattermark.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Mattermark\naid: mattermark\nurl: https://mattermark.com/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You represent that you are not located in a country that is subject to a U.S. Government embargo\nentity_types:\n- type: business\n  text: the entity or company that you represent\nrestricted_uses:\n- summary: Internal business use only\n  text: solely for your internal business purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: we alone will determine whether or not to approve your proposed account.\nminimum_age:\n  value: '18'\n  text:\
  \ you are at least 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/mattermark/eligibility/mattermark-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Mattermark's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Business Intelligence
- Company Data
- Investor
- Funding
- Sales Intelligence
- Market Research
---
