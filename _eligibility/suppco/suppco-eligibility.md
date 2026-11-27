---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: SuppCo makes no representations that the Services are appropriate or available for use in other locations.
  entity_types:
  - text: you are of at least eighteen (18) years of age
    type: individual
  minimum_age:
    text: you are of at least eighteen (18) years of age
    value: '18'
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
name: SuppCo
provenance_date: '2026-11-10'
provider_name: SuppCo
provider_slug: suppco
slug: suppco-eligibility
source_date: '2026-11-10'
source_filename: suppco-eligibility.yml
source_heading: Eligibility
source_page: https://supp.co/about/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: SuppCo\naid: suppco\nurl: https://supp.co/about/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: SuppCo makes no representations that the Services are appropriate or available for use in other locations.\nentity_types:\n- type: individual\n  text: you are of at least eighteen (18) years of age\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you are of at least eighteen (18) years of age\n"
source_yaml_url: https://artifacts.apis.io/suppco/eligibility/suppco-eligibility.yml
stated_fields:
- countries
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from SuppCo's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Supplements
- Health
- Wellness
- Nutrition
- Consumer App
- Mobile
- Health Data
---
