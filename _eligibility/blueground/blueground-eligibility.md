---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Site and services and programs mentioned are available only to individuals who are at least 18 years old, unless we specify otherwise.
    type: individual
  minimum_age:
    text: available only to individuals who are at least 18 years old
    value: '18'
  restricted_uses:
  - summary: Personal non-commercial use only
    text: A Visitor of the Site is allowed to use the Site only for personal, non-commercial purposes.
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
name: Blueground
provenance_date: '2026-11-09'
provider_name: Blueground
provider_slug: blueground
slug: blueground-eligibility
source_date: '2026-11-09'
source_filename: blueground-eligibility.yml
source_heading: Eligibility
source_page: https://www.theblueground.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Blueground\naid: blueground\nurl: https://www.theblueground.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Site and services and programs mentioned are available only to individuals who are at least 18 years\n    old, unless we specify otherwise.\nrestricted_uses:\n- summary: Personal non-commercial use only\n  text: A Visitor of the Site is allowed to use the Site only for personal, non-commercial purposes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n\
  \  text: available only to individuals who are at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/blueground/eligibility/blueground-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Blueground's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Real Estate
- PropTech
- Travel
- Hospitality
- Furnished Rentals
- Property Management
- Corporate Housing
- Marketplace
---
