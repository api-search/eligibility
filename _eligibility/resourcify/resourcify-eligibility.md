---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The offer to use the Services is intended solely for business customers.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Illegal or harmful content
    text: shall not use on the server any illegal or immoral content and/or such content which serves to incite the people, incites criminal offences or glorifies or trivializes violence
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
name: Resourcify
provenance_date: '2026-11-10'
provider_name: Resourcify
provider_slug: resourcify
slug: resourcify-eligibility
source_date: '2026-11-10'
source_filename: resourcify-eligibility.yml
source_heading: Eligibility
source_page: https://www.resourcify.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Resourcify\naid: resourcify\nurl: https://www.resourcify.com/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The offer to use the Services is intended solely for business customers.\nrestricted_uses:\n- summary: Illegal or harmful content\n  text: shall not use on the server any illegal or immoral content and/or such content which serves to incite the\n    people, incites criminal offences or glorifies or trivializes violence\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/resourcify/eligibility/resourcify-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Resourcify's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Waste Management
- Recycling
- Circular Economy
- Sustainability
- ESG
- Supply Chain
- Software-as-a-Service
---
