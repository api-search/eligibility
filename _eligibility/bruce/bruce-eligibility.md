---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old and hold an active professional license in the category you select at registration.
    type: individual
  minimum_age:
    text: You must be at least 18 years old
    value: '18'
  restricted_uses:
  - summary: Scraping or automated collection
    text: Scraping, harvesting, or automated collection of data
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Bruce conducts an initial license verification at the time of member onboarding.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Bruce
provenance_date: '2026-11-09'
provider_name: Bruce
provider_slug: bruce
slug: bruce-eligibility
source_date: '2026-11-09'
source_filename: bruce-eligibility.yml
source_heading: Eligibility
source_page: https://bruce.bot/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bruce\naid: bruce\nurl: https://bruce.bot/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old and hold an active professional license in the category you select at\n    registration.\nrestricted_uses:\n- summary: Scraping or automated collection\n  text: Scraping, harvesting, or automated collection of data\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Bruce conducts an initial license verification at the time of member onboarding.\nminimum_age:\n  value: '18'\n  text:\
  \ You must be at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/bruce/eligibility/bruce-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Bruce's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Marketplace
- Real Estate
- Mortgage
- Insurance
- Title and Escrow
- Reputation
- Professional Network
- Artificial Intelligence
---
