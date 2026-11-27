---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You represent and warrant that (i) You are not located in a country that is subject to the United States government embargo
  entity_types:
  - text: You means the individual accessing or using the Service
    type: individual
  - text: or the company, or other legal entity on behalf of which such individual is accessing or using the Service
    type: business
  minimum_age:
    text: null
    value: null
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
name: Loop
provenance_date: '2026-11-09'
provider_name: Loop
provider_slug: evloop-io
slug: evloop-io-eligibility
source_date: '2026-11-09'
source_filename: evloop-io-eligibility.yml
source_heading: Eligibility
source_page: https://www.loopglobal.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Loop\naid: evloop-io\nurl: https://www.loopglobal.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You represent and warrant that (i) You are not located in a country that is subject to the United States\n    government embargo\nentity_types:\n- type: individual\n  text: You means the individual accessing or using the Service\n- type: business\n  text: or the company, or other legal entity on behalf of which such individual is accessing or using the Service\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/evloop-io/eligibility/evloop-io-eligibility.yml
stated_fields:
- countries
- entity_types
summary_line: 3 quoted statements, read from Loop's own page on 2026-11-09.
synthetic: false
tags:
- Company
- EV Charging
- Infrastructure
- Sustainable
- Software
---
