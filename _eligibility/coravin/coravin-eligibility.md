---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Our Services are controlled and operated from within the United States.
  minimum_age:
    text: you are older than the legal drinking age wherever you are using the Services.
    value: legal drinking age
  restricted_uses:
  - summary: No reselling of merchandise
    text: any suspected resale of merchandise for personal and/or business profit is strictly prohibited.
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
name: Coravin
provenance_date: '2026-11-09'
provider_name: Coravin
provider_slug: coravin
slug: coravin-eligibility
source_date: '2026-11-09'
source_filename: coravin-eligibility.yml
source_heading: Eligibility
source_page: https://www.coravin.com/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Coravin\naid: coravin\nurl: https://www.coravin.com/policies/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Our Services are controlled and operated from within the United States.\nentity_types: []\nrestricted_uses:\n- summary: No reselling of merchandise\n  text: any suspected resale of merchandise for personal and/or business profit is strictly prohibited.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: legal drinking age\n  text: you are older than the legal drinking age wherever you are using the Services.\n"
source_yaml_url: https://artifacts.apis.io/coravin/eligibility/coravin-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Coravin's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Wine
- Beverages
- Consumer Products
- E-Commerce
- Shopify
- Agentic Commerce
- Universal Commerce Protocol
- Wine Preservation
---
