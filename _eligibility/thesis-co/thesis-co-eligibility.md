---
claim_count: 5
description: ''
doc:
  countries:
    excluded:
    - IR
    - CU
    - KP
    - SY
    - MM
    served: []
    text: you must not be a resident, citizen or agent of, or incorporated in, and do not have a registered office in Iran, Cuba, North Korea, Syria, Myanmar (Burma), the regions of Crimea, Donetsk or Luhansk
  entity_types:
  - text: if you are entering into these Terms of Use as an individual, then you are of legal age in the jurisdiction in which you reside
    type: individual
  - text: if you are entering into these Terms of Use as an entity, then you must have the legal authority to accept these Terms of Use on that entity’s behalf
    type: business
  minimum_age:
    text: you are of legal age in the jurisdiction in which you reside
    value: null
  restricted_uses:
  - summary: Sanctioned persons
    text: you are not the subject of economic or trade sanctions administered or enforced by any governmental authority
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- IR
- CU
- KP
- SY
- MM
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Thesis
provenance_date: '2026-11-10'
provider_name: Thesis
provider_slug: thesis-co
slug: thesis-co-eligibility
source_date: '2026-11-10'
source_filename: thesis-co-eligibility.yml
source_heading: Eligibility
source_page: https://thesis.co/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Thesis\naid: thesis-co\nurl: https://thesis.co/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - IR\n  - CU\n  - KP\n  - SY\n  - MM\n  text: you must not be a resident, citizen or agent of, or incorporated in, and do not have a registered office\n    in Iran, Cuba, North Korea, Syria, Myanmar (Burma), the regions of Crimea, Donetsk or Luhansk\nentity_types:\n- type: individual\n  text: if you are entering into these Terms of Use as an individual, then you are of legal age in the jurisdiction\n    in which you reside\n- type: business\n  text: if you are entering into these Terms\
  \ of Use as an entity, then you must have the legal authority to accept\n    these Terms of Use on that entity’s behalf\nrestricted_uses:\n- summary: Sanctioned persons\n  text: you are not the subject of economic or trade sanctions administered or enforced by any governmental authority\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: you are of legal age in the jurisdiction in which you reside\n"
source_yaml_url: https://artifacts.apis.io/thesis-co/eligibility/thesis-co-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Thesis's own page on 2026-11-10.
synthetic: false
tags:
- Venture Studio
- Bitcoin
- decentralized products
- Cryptocurrency
- Blockchain
---
