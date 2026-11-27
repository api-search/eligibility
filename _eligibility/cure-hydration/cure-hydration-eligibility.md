---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: By agreeing to these Terms of Service, you represent that you are at least the age of majority in your state or province of residence
    type: individual
  minimum_age:
    text: You may not use or engage with the Platform if you are under thirteen (13) years of age.
    value: '13'
  restricted_uses:
  - summary: Illegal or unauthorized use
    text: You may not use our products for any illegal or unauthorized purpose
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
name: Cure Hydration
provenance_date: '2026-11-09'
provider_name: Cure Hydration
provider_slug: cure-hydration
slug: cure-hydration-eligibility
source_date: '2026-11-09'
source_filename: cure-hydration-eligibility.yml
source_heading: Eligibility
source_page: https://www.curehydration.com/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cure Hydration\naid: cure-hydration\nurl: https://www.curehydration.com/policies/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: By agreeing to these Terms of Service, you represent that you are at least the age of majority in your state\n    or province of residence\nrestricted_uses:\n- summary: Illegal or unauthorized use\n  text: You may not use our products for any illegal or unauthorized purpose\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text:\
  \ You may not use or engage with the Platform if you are under thirteen (13) years of age.\n"
source_yaml_url: https://artifacts.apis.io/cure-hydration/eligibility/cure-hydration-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Cure Hydration's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer Packaged Goods
- Beverages
- Health and Wellness
- E-Commerce
- Direct to Consumer
- Retail
- Shopify
- Agentic Commerce
- Universal Commerce Protocol
- MCP
- GraphQL
---
