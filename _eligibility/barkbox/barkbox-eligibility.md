---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Platforms and the Services contain products or references to products that are only available within the United States and U.S. territories.
  entity_types:
  - text: BARK Services are available only to, and may only be used by, individuals who are 18 years and older who can form legally binding contracts under applicable law.
    type: individual
  minimum_age:
    text: BARK Services are available only to, and may only be used by, individuals who are 18 years and older
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
name: BARK (BarkBox)
provenance_date: '2026-11-09'
provider_name: BARK (BarkBox)
provider_slug: barkbox
slug: barkbox-eligibility
source_date: '2026-11-09'
source_filename: barkbox-eligibility.yml
source_heading: Eligibility
source_page: https://bark.co/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BARK (BarkBox)\naid: barkbox\nurl: https://bark.co/policies/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Platforms and the Services contain products or references to products that are only available within\n    the United States and U.S. territories.\nentity_types:\n- type: individual\n  text: BARK Services are available only to, and may only be used by, individuals who are 18 years and older who\n    can form legally binding contracts under applicable law.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: '18'\n  text: BARK Services are available only to, and may only be used by, individuals who are 18 years and older\n"
source_yaml_url: https://artifacts.apis.io/barkbox/eligibility/barkbox-eligibility.yml
stated_fields:
- countries
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from BARK (BarkBox)'s own page on 2026-11-09.
synthetic: false
tags:
- Company
- Pets
- E-Commerce
- Subscription
- Consumer
- Direct to Consumer
- Retail
---
