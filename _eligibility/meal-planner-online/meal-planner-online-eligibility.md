---
api_specs:
- filename: meal-planner-online.openapi.json
  format: json
  label: Meal Planner Read-only API
  slug: meal-planner-read-only-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/meal-planner-online/openapi/meal-planner-online.openapi.json
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Use the service only if you can enter a binding agreement under the law that applies to you.
    type: individual
  minimum_age:
    text: Accounts are intended for adults planning household meals, not for children to use independently.
    value: adult
  restricted_uses:
  - summary: Personal household use
    text: use the service for personal household planning unless a separate agreement permits otherwise.
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
name: meal-planner-online
provenance_date: '2026-11-10'
provider_name: meal-planner-online
provider_slug: meal-planner-online
slug: meal-planner-online-eligibility
source_date: '2026-11-10'
source_filename: meal-planner-online-eligibility.yml
source_heading: Eligibility
source_page: https://www.meal-planner.online/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: meal-planner-online\naid: meal-planner-online\nurl: https://www.meal-planner.online/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Use the service only if you can enter a binding agreement under the law that applies to you.\nrestricted_uses:\n- summary: Personal household use\n  text: use the service for personal household planning unless a separate agreement permits otherwise.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: adult\n  text: Accounts are intended for adults\
  \ planning household meals, not for children to use independently.\n"
source_yaml_url: https://artifacts.apis.io/meal-planner-online/eligibility/meal-planner-online-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from meal-planner-online's own page on 2026-11-10.
synthetic: false
tags:
- Meal Planning
- Family
- Canada
- Subscription
- Cooking
---
