---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Services may be accessed from countries other than the United States.
  entity_types:
  - text: Orders may only be placed using the Services for personal use and not for resale.
    type: individual
  minimum_age:
    text: By using the Services, you represent that you are 18 years old or older
    value: '18'
  restricted_uses:
  - summary: No resale or commercial use
    text: Orders may only be placed using the Services for personal use and not for resale.
  - summary: No commercial use of license
    text: and not for any commercial use or use on behalf of any third party, except as explicitly permitted by us in writing in advance
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
name: M.Gemi
provenance_date: '2026-11-10'
provider_name: M.Gemi
provider_slug: m-gemi
slug: m-gemi-eligibility
source_date: '2026-11-10'
source_filename: m-gemi-eligibility.yml
source_heading: Eligibility
source_page: https://mgemi.com/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: M.Gemi\naid: m-gemi\nurl: https://mgemi.com/policies/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Services may be accessed from countries other than the United States.\nentity_types:\n- type: individual\n  text: Orders may only be placed using the Services for personal use and not for resale.\nrestricted_uses:\n- summary: No resale or commercial use\n  text: Orders may only be placed using the Services for personal use and not for resale.\n- summary: No commercial use of license\n  text: and not for any commercial use or use on behalf of any third party, except\
  \ as explicitly permitted by us\n    in writing in advance\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: By using the Services, you represent that you are 18 years old or older\n"
source_yaml_url: https://artifacts.apis.io/m-gemi/eligibility/m-gemi-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from M.Gemi's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Retail
- E-Commerce
- Fashion
- Footwear
- Direct to Consumer
- Agentic Commerce
- Universal Commerce Protocol
- MCP
- Shopify
- Catalog
- Checkout
---
