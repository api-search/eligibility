---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No gambling use
    text: You must not use the Services for any purpose relating to gambling, gaming, betting, lotteries, sweepstakes, prize competitions or any gambling-related activity.
  - summary: No marketing use
    text: You must not use the Services for any purpose relating to the marketing, advertising, promotion, sale or supply of any product, service or commercial offering.
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
name: Meltano
provenance_date: '2026-11-10'
provider_name: Meltano
provider_slug: meltano
slug: meltano-eligibility
source_date: '2026-11-10'
source_filename: meltano-eligibility.yml
source_heading: Eligibility
source_page: https://meltano.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Meltano\naid: meltano\nurl: https://meltano.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: No gambling use\n  text: You must not use the Services for any purpose relating to gambling, gaming, betting, lotteries, sweepstakes,\n    prize competitions or any gambling-related activity.\n- summary: No marketing use\n  text: You must not use the Services for any purpose relating to the marketing, advertising, promotion, sale or\n    supply of any product, service or commercial offering.\nverification:\n  kyc: null\n\
  \  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/meltano/eligibility/meltano-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 2 quoted statements, read from Meltano's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Enterprise
- Data Integration
- ELT
- Data Pipeline
- Data Engineering
- Open Source
- DataOps
- Singer
---
