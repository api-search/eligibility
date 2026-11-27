---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: All references to “Buyer” shall include all parent(s), subsidiaries and affiliates of the entity placing the order.
    type: business
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: all orders are subject to Seller’s continuing approval of Buyer’s credit.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Coremins
provenance_date: '2026-11-09'
provider_name: Coremins
provider_slug: coremins
slug: coremins-eligibility
source_date: '2026-11-09'
source_filename: coremins-eligibility.yml
source_heading: Eligibility
source_page: https://coreandmain.com/terms-of-sale/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Coremins\naid: coremins\nurl: https://coreandmain.com/terms-of-sale/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: All references to “Buyer” shall include all parent(s), subsidiaries and affiliates of the entity placing\n    the order.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: all orders are subject to Seller’s continuing approval of Buyer’s credit.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/coremins/eligibility/coremins-eligibility.yml
stated_fields:
- entity_types
- verification
summary_line: 2 quoted statements, read from Coremins's own page on 2026-11-09.
synthetic: false
tags:
- Water
- Infrastructure
- Utilities
- Engineering
- Sustainability
- Company
---
