---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: you are at least 18 years of age if an individual
    type: individual
  minimum_age:
    text: you are at least 18 years of age if an individual
    value: '18'
  restricted_uses:
  - summary: Lawful purposes only
    text: you will use the Services only for lawful purposes and in accordance with this Agreement and all applicable policies and guidelines, including the AUP
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You must register and accept the terms of this Agreement and the AUP in order to use the Services.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: CastHost
provenance_date: '2026-11-09'
provider_name: CastHost
provider_slug: casthost-net
slug: casthost-net-eligibility
source_date: '2026-11-09'
source_filename: casthost-net-eligibility.yml
source_heading: Eligibility
source_page: https://www.casthost.net/terms_and_conditions.php
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CastHost\naid: casthost-net\nurl: https://www.casthost.net/terms_and_conditions.php\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: you are at least 18 years of age if an individual\nrestricted_uses:\n- summary: Lawful purposes only\n  text: you will use the Services only for lawful purposes and in accordance with this Agreement and all applicable\n    policies and guidelines, including the AUP\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You must register and accept the terms of this Agreement and the\
  \ AUP in order to use the Services.\nminimum_age:\n  value: '18'\n  text: you are at least 18 years of age if an individual\n"
source_yaml_url: https://artifacts.apis.io/casthost-net/eligibility/casthost-net-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from CastHost's own page on 2026-11-09.
synthetic: false
tags:
- Internet Radio
- Hosting
- Shoutcast
- Icecast
- cPanel
---
