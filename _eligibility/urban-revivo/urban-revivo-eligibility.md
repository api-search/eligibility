---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Shipping to > United States (footer selector only).
  entity_types:
  - text: By ordering goods through this website, you make sure that you have met the legal age required by Singapore Law to enter into a legally binding contract
    type: individual
  minimum_age:
    text: By ordering goods through this website, you make sure that you have met the legal age required by Singapore Law to enter into a legally binding contract
    value: null
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
name: Urban Revivo
provenance_date: '2026-11-10'
provider_name: Urban Revivo
provider_slug: urban-revivo
slug: urban-revivo-eligibility
source_date: '2026-11-10'
source_filename: urban-revivo-eligibility.yml
source_heading: Eligibility
source_page: https://global.urbanrevivo.com/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Urban Revivo\naid: urban-revivo\nurl: https://global.urbanrevivo.com/policies/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Shipping to > United States (footer selector only).\nentity_types:\n- type: individual\n  text: By ordering goods through this website, you make sure that you have met the legal age required by Singapore\n    Law to enter into a legally binding contract\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: By ordering goods through this website, you make\
  \ sure that you have met the legal age required by Singapore\n    Law to enter into a legally binding contract\n"
source_yaml_url: https://artifacts.apis.io/urban-revivo/eligibility/urban-revivo-eligibility.yml
stated_fields:
- countries
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from Urban Revivo's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Consumer
- Fashion
- Retail
- E-Commerce
- Apparel
- Agentic Commerce
---
