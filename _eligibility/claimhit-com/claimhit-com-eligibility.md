---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old to use the Service. One account per individual.
    type: individual
  - text: Team accounts are provided for legitimate professional use by teams and law firms.
    type: business
  minimum_age:
    text: You must be at least 18 years old to use the Service.
    value: '18'
  restricted_uses:
  - summary: Not a substitute for legal advice
    text: Use results as a substitute for qualified legal advice in legal proceedings without attorney review
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
name: claimhit-com
provenance_date: '2026-11-09'
provider_name: claimhit-com
provider_slug: claimhit-com
slug: claimhit-com-eligibility
source_date: '2026-11-09'
source_filename: claimhit-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.claimhit.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: claimhit-com\naid: claimhit-com\nurl: https://www.claimhit.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old to use the Service. One account per individual.\n- type: business\n  text: Team accounts are provided for legitimate professional use by teams and law firms.\nrestricted_uses:\n- summary: Not a substitute for legal advice\n  text: Use results as a substitute for qualified legal advice in legal proceedings without attorney review\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/claimhit-com/eligibility/claimhit-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from claimhit-com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Patents
- Intelligence
- Legal Tech
- IP
---
