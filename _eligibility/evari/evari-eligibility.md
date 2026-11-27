---
api_specs:
- filename: evari-quotes-api-openapi.yml
  format: yaml
  label: Evari Quotes API
  slug: evari-quotes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/evari/openapi/evari-quotes-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: as an individual, this agreement will be between Us and you as the individual
    type: individual
  - text: on behalf of a company, organisation or other entity (such as your employer), it will be the entity on whose behalf you are agreeing to this Agreement.
    type: business
  minimum_age:
    text: being over 18 years of age or of sufficient age
    value: '18'
  restricted_uses:
  - summary: Excluded Data
    text: 'Important: You must not use Evari to process Excluded Data.'
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
name: Evari
provenance_date: '2026-11-09'
provider_name: Evari
provider_slug: evari
slug: evari-eligibility
source_date: '2026-11-09'
source_filename: evari-eligibility.yml
source_heading: Eligibility
source_page: https://www.evari.tech/legal#terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Evari\naid: evari\nurl: https://www.evari.tech/legal#terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: as an individual, this agreement will be between Us and you as the individual\n- type: business\n  text: on behalf of a company, organisation or other entity (such as your employer), it will be the entity on whose\n    behalf you are agreeing to this Agreement.\nrestricted_uses:\n- summary: Excluded Data\n  text: 'Important: You must not use Evari to process Excluded Data.'\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: '18'\n  text: being over 18 years of age or of sufficient age\n"
source_yaml_url: https://artifacts.apis.io/evari/eligibility/evari-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Evari's own page on 2026-11-09.
synthetic: false
tags:
- Insurance
- Australia
- Insurtech
- Policy Administration
- Core Systems
- Property and Casualty
- Underwriting
- Claims
- Brokerage
- MGA
- Artificial Intelligence
- Quoting
- Endorsements
---
