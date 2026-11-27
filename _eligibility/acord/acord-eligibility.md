---
api_specs:
- filename: acord-claims-api-openapi.yml
  format: yaml
  label: ACORD Claims API
  slug: acord-claims-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/acord/openapi/acord-claims-api-openapi.yml
- filename: acord-party-api-openapi.yml
  format: yaml
  label: ACORD Party API
  slug: acord-party-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/acord/openapi/acord-party-api-openapi.yml
- filename: acord-policy-api-openapi.yml
  format: yaml
  label: ACORD Policy API
  slug: acord-policy-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/acord/openapi/acord-policy-api-openapi.yml
- filename: acord-underwriting-api-openapi.yml
  format: yaml
  label: ACORD Underwriting API
  slug: acord-underwriting-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/acord/openapi/acord-underwriting-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: access to it from territories where it is illegal is prohibited
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
name: ACORD
provenance_date: '2026-11-09'
provider_name: ACORD
provider_slug: acord
slug: acord-eligibility
source_date: '2026-11-09'
source_filename: acord-eligibility.yml
source_heading: Eligibility
source_page: https://www.acord.org/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ACORD\naid: acord\nurl: https://www.acord.org/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: access to it from territories where it is illegal is prohibited\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/acord/eligibility/acord-eligibility.yml
stated_fields:
- countries
summary_line: 1 quoted statement, read from ACORD's own page on 2026-11-09.
synthetic: false
tags:
- Claims
- Data Standards
- Insurance
- Policy
- Property and Casualty
- Reinsurance
- Standards
- Underwriting
- XML
---
