---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Setmore makes no claim that the Site, its services, are appropriate or accessible to other locations.
  minimum_age:
    text: The Site is not intended for and may not be used by individuals who are under thirteen years of age. By registering a Setmore account, the Site visitor or User promises that they are at least eighteen years of age.
    value: '18'
  restricted_uses:
  - summary: No competitive advantage or commercial use of Site
    text: The Site may not be used to gain or attempt to gain a competitive advantage in Setmore's industry market or be used for any commercial purpose.
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
name: Setmore
provenance_date: '2026-11-10'
provider_name: Setmore
provider_slug: setmore
slug: setmore-eligibility
source_date: '2026-11-10'
source_filename: setmore-eligibility.yml
source_heading: Eligibility
source_page: https://www.setmore.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Setmore\naid: setmore\nurl: https://www.setmore.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Setmore makes no claim that the Site, its services, are appropriate or accessible to other locations.\nentity_types: []\nrestricted_uses:\n- summary: No competitive advantage or commercial use of Site\n  text: The Site may not be used to gain or attempt to gain a competitive advantage in Setmore's industry market\n    or be used for any commercial purpose.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The\
  \ Site is not intended for and may not be used by individuals who are under thirteen years of age. By\n    registering a Setmore account, the Site visitor or User promises that they are at least eighteen years of age.\n"
source_yaml_url: https://artifacts.apis.io/setmore/eligibility/setmore-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Setmore's own page on 2026-11-10.
synthetic: false
tags:
- Scheduling
- Software-as-a-Service
- Appointment
- BusinessTools
- Company
---
