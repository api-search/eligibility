---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 'you/your/yours: means the relevant customer that wishes to purchase the Services being either you the individual'
    type: individual
  - text: where you operate through a corporate entity, the relevant corporate entity identified by you when you create your Coconut Account
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
name: Coconut
provenance_date: '2026-11-09'
provider_name: Coconut
provider_slug: getcoconut-com
slug: getcoconut-com-eligibility
source_date: '2026-11-09'
source_filename: getcoconut-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.getcoconut.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Coconut\naid: getcoconut-com\nurl: https://www.getcoconut.com/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: 'you/your/yours: means the relevant customer that wishes to purchase the Services being either you the individual'\n- type: business\n  text: where you operate through a corporate entity, the relevant corporate entity identified by you when you create\n    your Coconut Account\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text:\
  \ null\n"
source_yaml_url: https://artifacts.apis.io/getcoconut-com/eligibility/getcoconut-com-eligibility.yml
stated_fields:
- entity_types
summary_line: 2 quoted statements, read from Coconut's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Accounting
- Software-as-a-Service
---
