---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: 'You hereby represent and warrant that: (a) you are not located in a country that is subject to a U.S. Government embargo or that has been designated by the U.S. Government as a "terrorist supporting" country; and (b) you are not listed on any U.S. Government list of prohibited or restricted parties.'
  entity_types:
  - text: use the Service only for personal, non-commercial purposes
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Personal, non-commercial use only
    text: use the Service only for personal, non-commercial purposes;
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
name: Chaevi
provenance_date: '2026-11-09'
provider_name: Chaevi
provider_slug: chaevi
slug: chaevi-eligibility
source_date: '2026-11-09'
source_filename: chaevi-eligibility.yml
source_heading: Eligibility
source_page: https://www.chaevi.com/en/etc/agreement.php
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Chaevi\naid: chaevi\nurl: https://www.chaevi.com/en/etc/agreement.php\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: 'You hereby represent and warrant that: (a) you are not located in a country that is subject to a U.S. Government\n    embargo or that has been designated by the U.S. Government as a \"terrorist supporting\" country; and (b) you\n    are not listed on any U.S. Government list of prohibited or restricted parties.'\nentity_types:\n- type: individual\n  text: use the Service only for personal, non-commercial purposes\nrestricted_uses:\n- summary: Personal, non-commercial\
  \ use only\n  text: use the Service only for personal, non-commercial purposes;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/chaevi/eligibility/chaevi-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Chaevi's own page on 2026-11-09.
synthetic: false
tags:
- EV Charging
- Charging Stations
- Mobility
- Charging App
- Membership
- Customer Lounge
---
