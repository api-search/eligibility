---
api_specs:
- filename: carddeals-co-gift-card-deals-api-openapi.yml
  format: yaml
  label: CardDeals Gift-card deals API
  slug: carddeals-co-gift-card-deals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/carddeals-co/openapi/carddeals-co-gift-card-deals-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: If you are a consumer in the EU/EEA or UK, this clause does not affect mandatory consumer rights under the laws of your country of residence.
  entity_types:
  - text: You must be at least 18 years old, or the age of majority where you live, to create an account or buy a card from CardDeals.
    type: individual
  minimum_age:
    text: You must be at least 18 years old, or the age of majority where you live, to create an account or buy a card from CardDeals.
    value: '18'
  restricted_uses:
  - summary: Illegal or unauthorized purposes
    text: Use the Service for any illegal or unauthorized purpose
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: To buy a card we source from a supply partner, you must first verify your identity with our verification provider, Didit.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: CardDeals
provenance_date: '2026-11-09'
provider_name: CardDeals
provider_slug: carddeals-co
slug: carddeals-co-eligibility
source_date: '2026-11-09'
source_filename: carddeals-co-eligibility.yml
source_heading: Eligibility
source_page: https://carddeals.co/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CardDeals\naid: carddeals-co\nurl: https://carddeals.co/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: If you are a consumer in the EU/EEA or UK, this clause does not affect mandatory consumer rights under the\n    laws of your country of residence.\nentity_types:\n- type: individual\n  text: You must be at least 18 years old, or the age of majority where you live, to create an account or buy a\n    card from CardDeals.\nrestricted_uses:\n- summary: Illegal or unauthorized purposes\n  text: Use the Service for any illegal or unauthorized purpose\nverification:\n  kyc: true\n\
  \  kyb: null\n  approval_required: null\n  text: To buy a card we source from a supply partner, you must first verify your identity with our verification\n    provider, Didit.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old, or the age of majority where you live, to create an account or buy a\n    card from CardDeals.\n"
source_yaml_url: https://artifacts.apis.io/carddeals-co/eligibility/carddeals-co-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from CardDeals's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Gift Cards
- Comparison
- Discounts
- E-Commerce
- Real-Time
---
