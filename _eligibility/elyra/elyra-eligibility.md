---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Services are not intended for use in any jurisdiction where such use is unlawful or would subject us to registration or other compliance obligations.
  entity_types:
  - text: Operator accounts are for the subscribing business and its authorized staff only
    type: business
  - text: an individual diner using our booking channels
    type: individual
  minimum_age:
    text: The Services are intended for users at least 13 years of age.
    value: '13'
  restricted_uses:
  - summary: Unlawful jurisdictions
    text: The Services are not intended for use in any jurisdiction where such use is unlawful or would subject us to registration or other compliance obligations.
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
name: Elyra
provenance_date: '2026-11-09'
provider_name: Elyra
provider_slug: elyra
slug: elyra-eligibility
source_date: '2026-11-09'
source_filename: elyra-eligibility.yml
source_heading: Eligibility
source_page: https://www.elyrasystems.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Elyra\naid: elyra\nurl: https://www.elyrasystems.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Services are not intended for use in any jurisdiction where such use is unlawful or would subject us\n    to registration or other compliance obligations.\nentity_types:\n- type: business\n  text: Operator accounts are for the subscribing business and its authorized staff only\n- type: individual\n  text: an individual diner using our booking channels\nrestricted_uses:\n- summary: Unlawful jurisdictions\n  text: The Services are not intended for use in any jurisdiction where\
  \ such use is unlawful or would subject us\n    to registration or other compliance obligations.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: The Services are intended for users at least 13 years of age.\n"
source_yaml_url: https://artifacts.apis.io/elyra/eligibility/elyra-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Elyra's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Restaurant Technology
- Reservations
- Artificial Intelligence
- Hospitality
- Voice Agents
- Software-as-a-Service
---
