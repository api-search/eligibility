---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: we make no representation that the Materials included in the RapidSOS Service are appropriate or available for use in other locations.
  entity_types:
  - text: if you are an authorized government agency, you acknowledge your legal obligation to treat all emergency data that you may receive from RapidSOS
    type: government
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Prior suspension
    text: you have not previously been suspended or removed from the RapidSOS Service
  - summary: Illegal use
    text: use RapidSOS Service for any illegal purpose or in violation of any local, state, national, or international law;
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
name: RapidSOS
provenance_date: '2026-11-10'
provider_name: RapidSOS
provider_slug: rapidsos
slug: rapidsos-eligibility
source_date: '2026-11-10'
source_filename: rapidsos-eligibility.yml
source_heading: Eligibility
source_page: https://rapidsos.com/legal/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: RapidSOS\naid: rapidsos\nurl: https://rapidsos.com/legal/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: we make no representation that the Materials included in the RapidSOS Service are appropriate or available\n    for use in other locations.\nentity_types:\n- type: government\n  text: if you are an authorized government agency, you acknowledge your legal obligation to treat all emergency\n    data that you may receive from RapidSOS\nrestricted_uses:\n- summary: Prior suspension\n  text: you have not previously been suspended or removed from the\
  \ RapidSOS Service\n- summary: Illegal use\n  text: use RapidSOS Service for any illegal purpose or in violation of any local, state, national, or international\n    law;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/rapidsos/eligibility/rapidsos-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from RapidSOS's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Emergency Response
- Public Safety
- Safety
- Emergency Data
- Location
- IoT
- Alerts
---
