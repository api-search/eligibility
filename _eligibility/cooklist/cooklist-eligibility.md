---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You can't use Cooklist if it would be prohibited by U.S. sanctions.
  entity_types:
  - text: For the purpose of these Terms, a User is an individual who uses our Service.
    type: individual
  minimum_age:
    text: You must be at least 13 years old.
    value: '13'
  restricted_uses:
  - summary: Commercial music use
    text: Use of music for commercial or non-personal purposes in particular is prohibited unless you have obtained appropriate licenses.
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
name: Cooklist
provenance_date: '2026-11-09'
provider_name: Cooklist
provider_slug: cooklist
slug: cooklist-eligibility
source_date: '2026-11-09'
source_filename: cooklist-eligibility.yml
source_heading: Eligibility
source_page: https://cooklist.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cooklist\naid: cooklist\nurl: https://cooklist.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You can't use Cooklist if it would be prohibited by U.S. sanctions.\nentity_types:\n- type: individual\n  text: For the purpose of these Terms, a User is an individual who uses our Service.\nrestricted_uses:\n- summary: Commercial music use\n  text: Use of music for commercial or non-personal purposes in particular is prohibited unless you have obtained\n    appropriate licenses.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: '13'\n  text: You must be at least 13 years old.\n"
source_yaml_url: https://artifacts.apis.io/cooklist/eligibility/cooklist-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Cooklist's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Agentic Commerce
- Grocery
- Retail
- AI Assistant
- MCP
- Recipes
- Meal Planning
- E-Commerce
- Personalization
---
