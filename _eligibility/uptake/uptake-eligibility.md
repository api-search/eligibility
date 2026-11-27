---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Customer Affiliates may purchase Products from Uptake by executing an Order Form which is governed by the terms of this Agreement.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Acceptable use restrictions
    text: (b) for illegal, threatening, or offensive uses, or for similarly objectionable purposes
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
name: Uptake
provenance_date: '2026-11-10'
provider_name: Uptake
provider_slug: uptake
slug: uptake-eligibility
source_date: '2026-11-10'
source_filename: uptake-eligibility.yml
source_heading: Eligibility
source_page: https://uptake.com/legal/master-subscription-agreement/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Uptake\naid: uptake\nurl: https://uptake.com/legal/master-subscription-agreement/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Customer Affiliates may purchase Products from Uptake by executing an Order Form which is governed by the\n    terms of this Agreement.\nrestricted_uses:\n- summary: Acceptable use restrictions\n  text: (b) for illegal, threatening, or offensive uses, or for similarly objectionable purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text:\
  \ null\n"
source_yaml_url: https://artifacts.apis.io/uptake/eligibility/uptake-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Uptake's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Industrial AI
- Predictive Maintenance
- Asset Performance Management
- Fleet Management
- Telematics
- Machine Learning
- Industrial IoT
- Industrial
---
