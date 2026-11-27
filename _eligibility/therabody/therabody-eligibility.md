---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: To purchase certain products, services sold on the Service, we may require you to be of sufficient legal age as specifically indicated in any Additional Terms posted on the Service.
    value: null
  restricted_uses:
  - summary: Medical use restriction
    text: THE PRODUCTS PROVIDED BY THERABODY ARE NOT INTENDED FOR USE IN THE TREATMENT OR MANAGEMENT OF ANY DISEASES OR CONDITIONS
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
name: Therabody
provenance_date: '2026-11-10'
provider_name: Therabody
provider_slug: therabody
slug: therabody-eligibility
source_date: '2026-11-10'
source_filename: therabody-eligibility.yml
source_heading: Eligibility
source_page: https://www.therabody.com/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Therabody\naid: therabody\nurl: https://www.therabody.com/policies/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Medical use restriction\n  text: THE PRODUCTS PROVIDED BY THERABODY ARE NOT INTENDED FOR USE IN THE TREATMENT OR MANAGEMENT OF ANY DISEASES\n    OR CONDITIONS\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: To purchase certain products, services sold on the Service, we may require you to be of sufficient legal\n\
  \    age as specifically indicated in any Additional Terms posted on the Service.\n"
source_yaml_url: https://artifacts.apis.io/therabody/eligibility/therabody-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Therabody's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Wellness
- Health
- Consumer Products
- E-Commerce
- Retail
- Shopify
- Agentic Commerce
- MCP
- GraphQL
- Universal Commerce Protocol
---
