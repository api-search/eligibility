---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Unless otherwise specified, the Sites and the Contents are intended to promote Gap Inc.'s products and services available in the United States.
  entity_types:
  - text: You must be age 16 or older to use the Sites.
    type: individual
  minimum_age:
    text: You must be age 16 or older to use the Sites.
    value: '16'
  restricted_uses:
  - summary: Non-commercial use only
    text: The Sites and the Contents are intended solely for personal, non-commercial use.
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
name: Gap
provenance_date: '2026-11-09'
provider_name: Gap
provider_slug: gap
slug: gap-eligibility
source_date: '2026-11-09'
source_filename: gap-eligibility.yml
source_heading: Eligibility
source_page: https://www.gap.com/customer-service/terms-of-use?cid=6754
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Gap\naid: gap\nurl: https://www.gap.com/customer-service/terms-of-use?cid=6754\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Unless otherwise specified, the Sites and the Contents are intended to promote Gap Inc.'s products and services\n    available in the United States.\nentity_types:\n- type: individual\n  text: You must be age 16 or older to use the Sites.\nrestricted_uses:\n- summary: Non-commercial use only\n  text: The Sites and the Contents are intended solely for personal, non-commercial use.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text:\
  \ null\nminimum_age:\n  value: '16'\n  text: You must be age 16 or older to use the Sites.\n"
source_yaml_url: https://artifacts.apis.io/gap/eligibility/gap-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Gap's own page on 2026-11-09.
synthetic: false
tags:
- Fortune 500
- Retail
- Apparel
- E-Commerce
- Fashion
- Consumer Goods
---
