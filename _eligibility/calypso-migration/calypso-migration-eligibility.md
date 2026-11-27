---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: To register for an Account, you must be a natural person at least 18 years of age.
    type: individual
  minimum_age:
    text: you must be a natural person at least 18 years of age
    value: '18'
  restricted_uses:
  - summary: No stock price manipulation
    text: Not attempt to manipulate stock prices.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Nasdaq reserves the right to refuse registration for any reason.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Calypso Migration
provenance_date: '2026-11-09'
provider_name: Calypso Migration
provider_slug: calypso-migration
slug: calypso-migration-eligibility
source_date: '2026-11-09'
source_filename: calypso-migration-eligibility.yml
source_heading: Eligibility
source_page: https://www.nasdaq.com/legal
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Calypso Migration\naid: calypso-migration\nurl: https://www.nasdaq.com/legal\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: To register for an Account, you must be a natural person at least 18 years of age.\nrestricted_uses:\n- summary: No stock price manipulation\n  text: Not attempt to manipulate stock prices.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Nasdaq reserves the right to refuse registration for any reason.\nminimum_age:\n  value: '18'\n  text: you must be a natural person at least 18 years\
  \ of age\n"
source_yaml_url: https://artifacts.apis.io/calypso-migration/eligibility/calypso-migration-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Calypso Migration's own page on 2026-11-09.
synthetic: false
tags:
- Capital Markets
- Data Migration
- Financial Technology
- Migration
- Trading
---
