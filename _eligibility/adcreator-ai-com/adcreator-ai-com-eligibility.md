---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old or the legal age of majority in your jurisdiction to create an account.
    type: individual
  minimum_age:
    text: You must be at least 18 years old or the legal age of majority in your jurisdiction to create an account.
    value: '18'
  restricted_uses:
  - summary: Illegal or hateful ad content
    text: Create ads that promote hate speech, violence, discrimination, or illegal products and services.
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
name: AdCreator AI
provenance_date: '2026-11-09'
provider_name: AdCreator AI
provider_slug: adcreator-ai-com
slug: adcreator-ai-com-eligibility
source_date: '2026-11-09'
source_filename: adcreator-ai-com-eligibility.yml
source_heading: Eligibility
source_page: https://adcreator-ai.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AdCreator AI\naid: adcreator-ai-com\nurl: https://adcreator-ai.com/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old or the legal age of majority in your jurisdiction to create an account.\nrestricted_uses:\n- summary: Illegal or hateful ad content\n  text: Create ads that promote hate speech, violence, discrimination, or illegal products and services.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least\
  \ 18 years old or the legal age of majority in your jurisdiction to create an account.\n"
source_yaml_url: https://artifacts.apis.io/adcreator-ai-com/eligibility/adcreator-ai-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from AdCreator AI's own page on 2026-11-09.
synthetic: false
tags:
- Advertising
- Artificial Intelligence
- Shopify
- Marketing
- E-Commerce
- Company
---
