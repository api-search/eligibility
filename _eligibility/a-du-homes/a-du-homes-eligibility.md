---
api_specs:
- filename: openapi.json
  format: json
  label: A-du API
  slug: a-du-api
  spec_type: OpenAPI
  url: https://a-du.homes/openapi.json
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: currently Los Angeles County, San Diego County and San Francisco, California, and New York City, New York
  entity_types:
  - text: Be at least 18 years of age
    type: individual
  - text: Property management companies, real estate investment firms, and other business entities may create business accounts.
    type: business
  minimum_age:
    text: Be at least 18 years of age
    value: '18'
  restricted_uses:
  - summary: Illegal purposes
    text: List or rent properties for illegal purposes
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: A-du requires Members to complete identity verification and background screening before certain platform features become available
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: A-du, LLC
provenance_date: '2026-11-09'
provider_name: A-du, LLC
provider_slug: a-du-homes
slug: a-du-homes-eligibility
source_date: '2026-11-09'
source_filename: a-du-homes-eligibility.yml
source_heading: Eligibility
source_page: https://a-du.homes/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: A-du, LLC\naid: a-du-homes\nurl: https://a-du.homes/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: currently Los Angeles County, San Diego County and San Francisco, California, and New York City, New York\nentity_types:\n- type: individual\n  text: Be at least 18 years of age\n- type: business\n  text: Property management companies, real estate investment firms, and other business entities may create business\n    accounts.\nrestricted_uses:\n- summary: Illegal purposes\n  text: List or rent properties for illegal purposes\nverification:\n  kyc: true\n \
  \ kyb: null\n  approval_required: null\n  text: A-du requires Members to complete identity verification and background screening before certain platform\n    features become available\nminimum_age:\n  value: '18'\n  text: Be at least 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/a-du-homes/eligibility/a-du-homes-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from A-du, LLC's own page on 2026-11-09.
synthetic: false
tags:
- Real Estate
- Property Management
- ADU
- Rentals
- Construction
---
