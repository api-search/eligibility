---
api_specs:
- filename: merqube-helper-api-openapi.yml
  format: yaml
  label: MerQube Helper API
  slug: merqube-helper-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/merqube/openapi/merqube-helper-api-openapi.yml
- filename: merqube-identifier-api-openapi.yml
  format: yaml
  label: MerQube Identifier API
  slug: merqube-identifier-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/merqube/openapi/merqube-identifier-api-openapi.yml
- filename: merqube-index-api-openapi.yml
  format: yaml
  label: MerQube Index API
  slug: merqube-index-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/merqube/openapi/merqube-index-api-openapi.yml
- filename: merqube-legacy-equity-security-api-openapi.yml
  format: yaml
  label: MerQube Legacy Equity Security API
  slug: merqube-legacy-equity-security-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/merqube/openapi/merqube-legacy-equity-security-api-openapi.yml
- filename: merqube-options-api-openapi.yml
  format: yaml
  label: MerQube Options API
  slug: merqube-options-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/merqube/openapi/merqube-options-api-openapi.yml
- filename: merqube-portfolio-handler-api-openapi.yml
  format: yaml
  label: MerQube Portfolio Handler API
  slug: merqube-portfolio-handler-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/merqube/openapi/merqube-portfolio-handler-api-openapi.yml
- filename: merqube-security-api-openapi.yml
  format: yaml
  label: MerQube Security API
  slug: merqube-security-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/merqube/openapi/merqube-security-api-openapi.yml
- filename: merqube-security-list-api-openapi.yml
  format: yaml
  label: MerQube Security List API
  slug: merqube-security-list-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/merqube/openapi/merqube-security-list-api-openapi.yml
- filename: merqube-merqube-api-api-openapi.yml
  format: yaml
  label: MerQube MerQube API
  slug: merqube-merqube-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/merqube/openapi/merqube-merqube-api-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: MerQube reserves the right to impose geographic or other access restrictions at any time.
  entity_types:
  - text: The Website is offered and available only to users who are eighteen (18) years of age or older.
    type: individual
  minimum_age:
    text: The Website is offered and available only to users who are eighteen (18) years of age or older.
    value: '18'
  restricted_uses:
  - summary: Sanctions and export control violations
    text: Violates any applicable law, regulation, or sanctions program, including export controls administered by the U.S. Department of Commerce and economic sanctions administered by OFAC.
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
name: MerQube
provenance_date: '2026-11-10'
provider_name: MerQube
provider_slug: merqube
slug: merqube-eligibility
source_date: '2026-11-10'
source_filename: merqube-eligibility.yml
source_heading: Eligibility
source_page: https://merqube.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: MerQube\naid: merqube\nurl: https://merqube.com/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: MerQube reserves the right to impose geographic or other access restrictions at any time.\nentity_types:\n- type: individual\n  text: The Website is offered and available only to users who are eighteen (18) years of age or older.\nrestricted_uses:\n- summary: Sanctions and export control violations\n  text: Violates any applicable law, regulation, or sanctions program, including export controls administered by\n    the U.S. Department of Commerce and economic sanctions administered\
  \ by OFAC.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Website is offered and available only to users who are eighteen (18) years of age or older.\n"
source_yaml_url: https://artifacts.apis.io/merqube/eligibility/merqube-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from MerQube's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Financial Services
- Index Data
- Market Data
- Capital Markets
- investment-strategies
- Asset Management
- ETFs
- Structured Products
- Quantitative Finance
- OpenAPI
---
