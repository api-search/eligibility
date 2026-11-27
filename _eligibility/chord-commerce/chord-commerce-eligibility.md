---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: IF YOU ARE ENTERING INTO THIS AGREEMENT ON BEHALF OF A COMPANY OR OTHER LEGAL ENTITY, YOU REPRESENT THAT YOU HAVE THE AUTHORITY TO BIND SUCH ENTITY TO THIS AGREEMENT
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Illegal or harmful activity (AUP)
    text: Do not use the Services to engage in or encourage any activity that is illegal, deceptive, harmful, a violation of others' rights, or harmful to Chord's business operations or reputation
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
name: Chord
provenance_date: '2026-11-09'
provider_name: Chord
provider_slug: chord-commerce
slug: chord-commerce-eligibility
source_date: '2026-11-09'
source_filename: chord-commerce-eligibility.yml
source_heading: Eligibility
source_page: https://chordcommerce.com/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Chord\naid: chord-commerce\nurl: https://chordcommerce.com/legal/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: IF YOU ARE ENTERING INTO THIS AGREEMENT ON BEHALF OF A COMPANY OR OTHER LEGAL ENTITY, YOU REPRESENT THAT\n    YOU HAVE THE AUTHORITY TO BIND SUCH ENTITY TO THIS AGREEMENT\nrestricted_uses:\n- summary: Illegal or harmful activity (AUP)\n  text: Do not use the Services to engage in or encourage any activity that is illegal, deceptive, harmful, a violation\n    of others' rights, or harmful to Chord's business\
  \ operations or reputation\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/chord-commerce/eligibility/chord-commerce-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Chord's own page on 2026-11-09.
synthetic: false
tags:
- Commerce
- Composable Commerce
- Headless Commerce
- Order Management
- OMS
- Customer Data Platform
- CDP
- Event Tracking
- Commerce Analytics
- Customer Lifetime Value
- AI Agents
- Commerce Copilot
- Solidus
- Spree
- Ruby on Rails
- Shopify
- Direct to Consumer
---
