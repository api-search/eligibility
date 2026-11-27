---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: any advertiser, media agency or intermediary that sends an Insertion Order to ADIKTEEV
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Sanctioned persons
    text: neither the Client, nor any person(s) or entity(ies) owning or controlling (whether individually or collectively) 50% or more of the Client is a person sanctioned by any applicable sanctions laws
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
name: Adikteev
provenance_date: '2026-11-09'
provider_name: Adikteev
provider_slug: adikteev
slug: adikteev-eligibility
source_date: '2026-11-09'
source_filename: adikteev-eligibility.yml
source_heading: Eligibility
source_page: https://www.adikteev.com/hubfs/Legal%20doc/Terms%20%26%20conditions%20June%202026.pdf
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Adikteev\naid: adikteev\nurl: https://www.adikteev.com/hubfs/Legal%20doc/Terms%20%26%20conditions%20June%202026.pdf\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: any advertiser, media agency or intermediary that sends an Insertion Order to ADIKTEEV\nrestricted_uses:\n- summary: Sanctioned persons\n  text: neither the Client, nor any person(s) or entity(ies) owning or controlling (whether individually or collectively)\n    50% or more of the Client is a person sanctioned by any applicable sanctions laws\nverification:\n  kyc: null\n\
  \  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/adikteev/eligibility/adikteev-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Adikteev's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Mobile
- Advertising
- Retargeting
- User Acquisition
---
