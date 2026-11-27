---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Hazardous materials
    text: Customer acknowledges that it is required to advise Company in advance of its intention to tender hazardous material goods
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
name: Silq
provenance_date: '2026-11-10'
provider_name: Silq
provider_slug: silq
slug: silq-eligibility
source_date: '2026-11-10'
source_filename: silq-eligibility.yml
source_heading: Eligibility
source_page: https://www.onesilq.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Silq\naid: silq\nurl: https://www.onesilq.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Hazardous materials\n  text: Customer acknowledges that it is required to advise Company in advance of its intention to tender hazardous\n    material goods\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/silq/eligibility/silq-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Silq's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Freight Forwarding
- Logistics
- Supply Chain
- Shipping
- Customs Brokerage
- Ocean Freight
- Air Freight
---
