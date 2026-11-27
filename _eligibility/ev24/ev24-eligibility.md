---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: User – an adult natural person with full legal capacity, or a legal entity owning or possessing an electric vehicle, using the Service.
    type: individual
  - text: Customer – an entity owning or managing Charging Stations, for which the Service Provider provides the Service.
    type: business
  minimum_age:
    text: User – an adult natural person with full legal capacity
    value: adult
  restricted_uses:
  - summary: Illegal use, fraud, financial abuse
    text: Using the Service for illegal purposes, fraud, or financial abuse is prohibited.
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
name: EV24
provenance_date: '2026-11-09'
provider_name: EV24
provider_slug: ev24
slug: ev24-eligibility
source_date: '2026-11-09'
source_filename: ev24-eligibility.yml
source_heading: Eligibility
source_page: https://docs.ev24.cloud/en/legal/client-terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: EV24\naid: ev24\nurl: https://docs.ev24.cloud/en/legal/client-terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: User – an adult natural person with full legal capacity, or a legal entity owning or possessing an electric\n    vehicle, using the Service.\n- type: business\n  text: Customer – an entity owning or managing Charging Stations, for which the Service Provider provides the Service.\nrestricted_uses:\n- summary: Illegal use, fraud, financial abuse\n  text: Using the Service for illegal purposes, fraud, or financial abuse\
  \ is prohibited.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: adult\n  text: User – an adult natural person with full legal capacity\n"
source_yaml_url: https://artifacts.apis.io/ev24/eligibility/ev24-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from EV24's own page on 2026-11-09.
synthetic: false
tags:
- EV Charging
- Platform
- Software-as-a-Service
- Energy
---
