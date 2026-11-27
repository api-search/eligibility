---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are a consumer, please note that these terms of use, their subject matter and their formation, are governed by Dutch law.
    type: individual
  - text: If you are a business, these terms of use, their subject matter and their formation (and any non-contractual disputes or claims) are governed by Dutch law.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Denial-of-service attacks
    text: You must not attack our site via a denial-of-service attack or a distributed denial-of service attack.
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
name: Fero
provenance_date: '2026-11-09'
provider_name: Fero
provider_slug: fero
slug: fero-eligibility
source_date: '2026-11-09'
source_filename: fero-eligibility.yml
source_heading: Eligibility
source_page: https://fero.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Fero\naid: fero\nurl: https://fero.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: If you are a consumer, please note that these terms of use, their subject matter and their formation, are\n    governed by Dutch law.\n- type: business\n  text: If you are a business, these terms of use, their subject matter and their formation (and any non-contractual\n    disputes or claims) are governed by Dutch law.\nrestricted_uses:\n- summary: Denial-of-service attacks\n  text: You must not attack our site via a denial-of-service\
  \ attack or a distributed denial-of service attack.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/fero/eligibility/fero-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Fero's own page on 2026-11-09.
synthetic: false
tags:
- Checkout
- Artificial Intelligence
- E-Commerce
- Conversion
- Analytics
---
