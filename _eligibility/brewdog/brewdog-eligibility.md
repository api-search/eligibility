---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - GB
    text: Promotions are open to UK residents; Northern Ireland is excluded from the free kegs promotion.
  entity_types:
  - text: You must be aged 18 or over to purchase alcohol.
    type: individual
  minimum_age:
    text: You must be aged 18 or over to purchase alcohol.
    value: '18'
  restricted_uses:
  - summary: Alcohol purchase age limit
    text: You must be aged 18 or over to purchase alcohol.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: When ordering and making a payment you will be required to confirm that you are aged 18 or over.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: BrewDog
provenance_date: '2026-11-09'
provider_name: BrewDog
provider_slug: brewdog
slug: brewdog-eligibility
source_date: '2026-11-09'
source_filename: brewdog-eligibility.yml
source_heading: Eligibility
source_page: https://brewdog.com/pages/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BrewDog\naid: brewdog\nurl: https://brewdog.com/pages/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - GB\n  excluded: []\n  text: Promotions are open to UK residents; Northern Ireland is excluded from the free kegs promotion.\nentity_types:\n- type: individual\n  text: You must be aged 18 or over to purchase alcohol.\nrestricted_uses:\n- summary: Alcohol purchase age limit\n  text: You must be aged 18 or over to purchase alcohol.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: When ordering and making a payment you will be required to\
  \ confirm that you are aged 18 or over.\nminimum_age:\n  value: '18'\n  text: You must be aged 18 or over to purchase alcohol.\n"
source_yaml_url: https://artifacts.apis.io/brewdog/eligibility/brewdog-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from BrewDog's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Food and Beverage
- Beer
- Brewing
- Retail
- E-Commerce
- Consumer Packaged Goods
- Hospitality
- Agentic Commerce
- Shopify
---
