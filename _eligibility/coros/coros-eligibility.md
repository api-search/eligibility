---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: If you choose to access this Service from locations outside of the United States, it is your responsibility to understand and obey all applicable local, state, federal, and international laws (including minimum age requirements)
  minimum_age:
    text: You must be 16 or older to register and use the Service and/or contribute User Submissions to the Service.
    value: '16'
  restricted_uses:
  - summary: Personal, non-commercial purchases
    text: You may only purchase products for personal, non-commercial use.
  - summary: Lawful use of products
    text: By placing an order, you represent that the products ordered will be used only in a lawful manner.
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
name: COROS
provenance_date: '2026-11-09'
provider_name: COROS
provider_slug: coros
slug: coros-eligibility
source_date: '2026-11-09'
source_filename: coros-eligibility.yml
source_heading: Eligibility
source_page: https://coros.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: COROS\naid: coros\nurl: https://coros.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: If you choose to access this Service from locations outside of the United States, it is your responsibility\n    to understand and obey all applicable local, state, federal, and international laws (including minimum age requirements)\nentity_types: []\nrestricted_uses:\n- summary: Personal, non-commercial purchases\n  text: You may only purchase products for personal, non-commercial use.\n- summary: Lawful use of products\n  text: By placing an order, you represent that the products ordered\
  \ will be used only in a lawful manner.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: You must be 16 or older to register and use the Service and/or contribute User Submissions to the Service.\n"
source_yaml_url: https://artifacts.apis.io/coros/eligibility/coros-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from COROS's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Wearables
- Fitness
- GPS Watches
- Sports Technology
- Health Data
- Webhook
- Authentication
- MCP
---
