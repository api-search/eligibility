---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You may not use the Service if you are a resident of a country embargoed by the United States or are a foreign person or entity blocked or denied by the United States government.
  minimum_age:
    text: You hereby affirm that you are at least 18 years old
    value: '18'
  restricted_uses:
  - summary: Objectionable activities
    text: You may not use the Service, or assist or encourage any other party to use the Service, to engage in any activity that Planet FWD deems objectionable
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
name: Planet FWD
provenance_date: '2026-11-10'
provider_name: Planet FWD
provider_slug: planet-fwd
slug: planet-fwd-eligibility
source_date: '2026-11-10'
source_filename: planet-fwd-eligibility.yml
source_heading: Eligibility
source_page: https://www.planetfwd.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Planet FWD\naid: planet-fwd\nurl: https://www.planetfwd.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You may not use the Service if you are a resident of a country embargoed by the United States or are a foreign\n    person or entity blocked or denied by the United States government.\nentity_types: []\nrestricted_uses:\n- summary: Objectionable activities\n  text: You may not use the Service, or assist or encourage any other party to use the Service, to engage in any\n    activity that Planet FWD deems objectionable\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: '18'\n  text: You hereby affirm that you are at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/planet-fwd/eligibility/planet-fwd-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Planet FWD's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Climate
- Sustainability
- Carbon Accounting
- Decarbonization
- Life Cycle Assessment
- Consumer Packaged Goods
- Supply Chain
---
