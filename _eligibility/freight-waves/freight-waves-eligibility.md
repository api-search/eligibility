---
api_specs:
- filename: freight-waves-authentication-api-openapi.yml
  format: yaml
  label: Freight Waves Authentication API
  slug: freight-waves-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/freight-waves/openapi/freight-waves-authentication-api-openapi.yml
- filename: freight-waves-data-api-openapi.yml
  format: yaml
  label: Freight Waves Data API
  slug: freight-waves-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/freight-waves/openapi/freight-waves-data-api-openapi.yml
- filename: freight-waves-lookup-api-openapi.yml
  format: yaml
  label: Freight Waves Lookup API
  slug: freight-waves-lookup-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/freight-waves/openapi/freight-waves-lookup-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Web Sites may not be accessed by individuals whose nationality is that of countries that are subject to a United States trade embargo.
  entity_types:
  - text: The Web Sites are offered and available to users who are at least 18 years of age or older.
    type: individual
  minimum_age:
    text: The Web Sites are offered and available to users who are at least 18 years of age or older.
    value: '18'
  restricted_uses:
  - summary: Lawful purposes only
    text: You may use the Web Sites only for lawful purposes and in accordance with these Terms of Use.
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
name: Freight Waves
provenance_date: '2026-11-09'
provider_name: Freight Waves
provider_slug: freight-waves
slug: freight-waves-eligibility
source_date: '2026-11-09'
source_filename: freight-waves-eligibility.yml
source_heading: Eligibility
source_page: https://www.freightwaves.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Freight Waves\naid: freight-waves\nurl: https://www.freightwaves.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Web Sites may not be accessed by individuals whose nationality is that of countries that are subject\n    to a United States trade embargo.\nentity_types:\n- type: individual\n  text: The Web Sites are offered and available to users who are at least 18 years of age or older.\nrestricted_uses:\n- summary: Lawful purposes only\n  text: You may use the Web Sites only for lawful purposes and in accordance with these Terms of Use.\nverification:\n  kyc:\
  \ null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Web Sites are offered and available to users who are at least 18 years of age or older.\n"
source_yaml_url: https://artifacts.apis.io/freight-waves/eligibility/freight-waves-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Freight Waves's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Freight
- Logistics
- Supply Chain
- Transportation
- Trucking
- Market Data
- Analytics
- Freight Rates
- Sonar
---
