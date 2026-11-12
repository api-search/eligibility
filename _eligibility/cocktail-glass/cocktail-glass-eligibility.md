---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: cocktail.glass publishes recipes for alcoholic drinks and is intended for adults.
    value: adults
  restricted_uses:
  - summary: Alcohol use restricted to adults where legal
    text: You are responsible for making, drinking, and serving these drinks only where it is legal to do so, and only at or above the legal drinking age where you are.
  verification:
    approval_required: false
    kyb: null
    kyc: false
    text: You do not need an account, an API key, or a subscription.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Cocktail Glass
provenance_date: '2026-11-09'
provider_name: Cocktail Glass
provider_slug: cocktail-glass
slug: cocktail-glass-eligibility
source_date: '2026-11-09'
source_filename: cocktail-glass-eligibility.yml
source_heading: Eligibility
source_page: https://cocktail.glass/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cocktail Glass\naid: cocktail-glass\nurl: https://cocktail.glass/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Alcohol use restricted to adults where legal\n  text: You are responsible for making, drinking, and serving these drinks only where it is legal to do so, and\n    only at or above the legal drinking age where you are.\nverification:\n  kyc: false\n  kyb: null\n  approval_required: false\n  text: You do not need an account, an API key, or a subscription.\nminimum_age:\n  value: adults\n  text: cocktail.glass\
  \ publishes recipes for alcoholic drinks and is intended for adults.\n"
source_yaml_url: https://artifacts.apis.io/cocktail-glass/eligibility/cocktail-glass-eligibility.yml
stated_fields:
- restricted_uses
- verification
- minimum_age
summary_line: 3 quoted statements, read from Cocktail Glass's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Cocktails
- Recipes
- Food and Drink
- MCP
- AI Agents
- Open Data
---
