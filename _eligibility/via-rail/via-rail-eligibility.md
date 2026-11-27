---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: As a condition of using our Site and purchasing our products and services, you acknowledge that you are at least 18 years of age (or the legal age in your province of residence)
    type: individual
  minimum_age:
    text: you acknowledge that you are at least 18 years of age (or the legal age in your province of residence)
    value: '18'
  restricted_uses:
  - summary: Bar for violations
    text: VIA Rail reserves the right to bar access to the Site to anyone who violates these Terms or applicable laws
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
name: VIA Rail Canada
provenance_date: '2026-11-10'
provider_name: VIA Rail Canada
provider_slug: via-rail
slug: via-rail-eligibility
source_date: '2026-11-10'
source_filename: via-rail-eligibility.yml
source_heading: Eligibility
source_page: https://www.viarail.ca/en/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: VIA Rail Canada\naid: via-rail\nurl: https://www.viarail.ca/en/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: As a condition of using our Site and purchasing our products and services, you acknowledge that you are\n    at least 18 years of age (or the legal age in your province of residence)\nrestricted_uses:\n- summary: Bar for violations\n  text: VIA Rail reserves the right to bar access to the Site to anyone who violates these Terms or applicable laws\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: '18'\n  text: you acknowledge that you are at least 18 years of age (or the legal age in your province of residence)\n"
source_yaml_url: https://artifacts.apis.io/via-rail/eligibility/via-rail-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from VIA Rail Canada's own page on 2026-11-10.
synthetic: false
tags:
- Travel
- Canada
- Rail
- Passenger Rail
- Transit
- GTFS
- Open Data
- Booking
- Distribution
- Travel Agents
- Crown Corporation
- Loyalty
---
