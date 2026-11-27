---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Supergoop! currently ships only to locations within the 50 United States
  entity_types:
  - text: You are only authorized to use the Services if you agree to abide by all applicable laws and these Terms.
    type: individual
  minimum_age:
    text: Supergoop!’s website and online services are not directed toward individuals under the age of 13
    value: '13'
  restricted_uses:
  - summary: Unlawful or harmful use
    text: 'you may not use the Services: (a) for any purpose that is unlawful under applicable federal, state, local or international law'
  verification:
    approval_required: false
    kyb: null
    kyc: null
    text: We may take steps to verify your identity to process your order
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Supergoop!
provenance_date: '2026-11-10'
provider_name: Supergoop!
provider_slug: supergoop
slug: supergoop-eligibility
source_date: '2026-11-10'
source_filename: supergoop-eligibility.yml
source_heading: Eligibility
source_page: https://supergoop.com/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Supergoop!\naid: supergoop\nurl: https://supergoop.com/policies/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Supergoop! currently ships only to locations within the 50 United States\nentity_types:\n- type: individual\n  text: You are only authorized to use the Services if you agree to abide by all applicable laws and these Terms.\nrestricted_uses:\n- summary: Unlawful or harmful use\n  text: 'you may not use the Services: (a) for any purpose that is unlawful under applicable federal, state, local\n    or international law'\nverification:\n  kyc: null\n  kyb:\
  \ null\n  approval_required: false\n  text: We may take steps to verify your identity to process your order\nminimum_age:\n  value: '13'\n  text: Supergoop!’s website and online services are not directed toward individuals under the age of 13\n"
source_yaml_url: https://artifacts.apis.io/supergoop/eligibility/supergoop-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Supergoop!'s own page on 2026-11-10.
synthetic: false
tags:
- Company
- Sunscreen
- Skincare
- Beauty
- Cosmetics
- Consumer Goods
- Retail
- E-Commerce
- Direct to Consumer
- Shopify
- Agentic Commerce
- Universal Commerce Protocol
- MCP
- GraphQL
---
