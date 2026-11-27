---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: By creating an account or using the Service, you confirm that you are at least 13 years old
    value: '13'
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
name: Cinevva
provenance_date: '2026-11-09'
provider_name: Cinevva
provider_slug: cinevva-com
slug: cinevva-com-eligibility
source_date: '2026-11-09'
source_filename: cinevva-com-eligibility.yml
source_heading: Eligibility
source_page: https://app.cinevva.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cinevva\naid: cinevva-com\nurl: https://app.cinevva.com/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: By creating an account or using the Service, you confirm that you are at least 13 years old\n"
source_yaml_url: https://artifacts.apis.io/cinevva-com/eligibility/cinevva-com-eligibility.yml
stated_fields:
- minimum_age
summary_line: 1 quoted statement, read from Cinevva's own page on 2026-11-09.
synthetic: false
tags:
- Gaming
- Artificial Intelligence
- Browser
- Platform
- Creative
---
