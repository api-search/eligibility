---
api_specs:
- filename: autoza-co-uk-dealers-api-openapi.yml
  format: yaml
  label: Autoza UK Dealers API
  slug: autoza-co-uk-dealers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/autoza-co-uk/openapi/autoza-co-uk-dealers-api-openapi.yml
- filename: autoza-co-uk-listing-api-openapi.yml
  format: yaml
  label: Autoza UK Listing API
  slug: autoza-co-uk-listing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/autoza-co-uk/openapi/autoza-co-uk-listing-api-openapi.yml
- filename: autoza-co-uk-makes-api-openapi.yml
  format: yaml
  label: Autoza UK Makes API
  slug: autoza-co-uk-makes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/autoza-co-uk/openapi/autoza-co-uk-makes-api-openapi.yml
- filename: autoza-co-uk-market-api-openapi.yml
  format: yaml
  label: Autoza UK Market API
  slug: autoza-co-uk-market-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/autoza-co-uk/openapi/autoza-co-uk-market-api-openapi.yml
- filename: autoza-co-uk-search-api-openapi.yml
  format: yaml
  label: Autoza UK Search API
  slug: autoza-co-uk-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/autoza-co-uk/openapi/autoza-co-uk-search-api-openapi.yml
- filename: autoza-co-uk-stats-api-openapi.yml
  format: yaml
  label: Autoza UK Stats API
  slug: autoza-co-uk-stats-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/autoza-co-uk/openapi/autoza-co-uk-stats-api-openapi.yml
- filename: autoza-co-uk-vehicles-api-openapi.yml
  format: yaml
  label: Autoza UK Vehicles API
  slug: autoza-co-uk-vehicles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/autoza-co-uk/openapi/autoza-co-uk-vehicles-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - GB
    text: Autoza is an online marketplace that introduces prospective vehicle buyers to dealers and private sellers in the United Kingdom.
  entity_types:
  - text: You are at least 18 years old and legally capable of forming a binding contract.
    type: individual
  - text: 'If you list vehicles as a trader (a "Dealer") you additionally agree that: You are a bona fide motor trader and will complete our verification process honestly.'
    type: business
  minimum_age:
    text: You are at least 18 years old and legally capable of forming a binding contract.
    value: '18'
  restricted_uses:
  - summary: Fraud, stolen or sanctioned vehicles
    text: Engage in fraud, money laundering, or the sale of stolen or sanctioned vehicles.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You are a bona fide motor trader and will complete our verification process honestly.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Autoza UK
provenance_date: '2026-11-09'
provider_name: Autoza UK
provider_slug: autoza-co-uk
slug: autoza-co-uk-eligibility
source_date: '2026-11-09'
source_filename: autoza-co-uk-eligibility.yml
source_heading: Eligibility
source_page: https://autoza.co.uk/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Autoza UK\naid: autoza-co-uk\nurl: https://autoza.co.uk/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - GB\n  excluded: []\n  text: Autoza is an online marketplace that introduces prospective vehicle buyers to dealers and private sellers\n    in the United Kingdom.\nentity_types:\n- type: individual\n  text: You are at least 18 years old and legally capable of forming a binding contract.\n- type: business\n  text: 'If you list vehicles as a trader (a \"Dealer\") you additionally agree that: You are a bona fide motor trader\n    and will complete our verification process honestly.'\nrestricted_uses:\n\
  - summary: Fraud, stolen or sanctioned vehicles\n  text: Engage in fraud, money laundering, or the sale of stolen or sanctioned vehicles.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You are a bona fide motor trader and will complete our verification process honestly.\nminimum_age:\n  value: '18'\n  text: You are at least 18 years old and legally capable of forming a binding contract.\n"
source_yaml_url: https://artifacts.apis.io/autoza-co-uk/eligibility/autoza-co-uk-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Autoza UK's own page on 2026-11-09.
synthetic: false
tags:
- Automotive
- Marketplace
- Artificial Intelligence
- Used Vehicles
- United Kingdom
---
