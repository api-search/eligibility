---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: primarily reside in one of the fifty United States or the District of Columbia
  entity_types:
  - text: 'our Services are available only to individuals who:'
    type: individual
  minimum_age:
    text: are at least eighteen (18) years of age (or the age of majority in your state of residence, if higher)
    value: '18'
  restricted_uses:
  - summary: Gift cards not for resale
    text: not for resale or any commercial purpose.
  - summary: Reserve value non-transferable
    text: may not be sold, gifted, pledged, or used as collateral.
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: you agree to provide us with the information we request for the purposes of identity verification
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Fold
provenance_date: '2026-11-09'
provider_name: Fold
provider_slug: fold
slug: fold-eligibility
source_date: '2026-11-09'
source_filename: fold-eligibility.yml
source_heading: Eligibility
source_page: https://foldapp.com/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Fold\naid: fold\nurl: https://foldapp.com/legal/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: primarily reside in one of the fifty United States or the District of Columbia\nentity_types:\n- type: individual\n  text: 'our Services are available only to individuals who:'\nrestricted_uses:\n- summary: Gift cards not for resale\n  text: not for resale or any commercial purpose.\n- summary: Reserve value non-transferable\n  text: may not be sold, gifted, pledged, or used as collateral.\nverification:\n  kyc: true\n  kyb: null\n  approval_required:\
  \ null\n  text: you agree to provide us with the information we request for the purposes of identity verification\nminimum_age:\n  value: '18'\n  text: are at least eighteen (18) years of age (or the age of majority in your state of residence, if higher)\n"
source_yaml_url: https://artifacts.apis.io/fold/eligibility/fold-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Fold's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Bitcoin
- Cryptocurrency
- Rewards
- Payments
- Personal Finance
- Debit Cards
---
