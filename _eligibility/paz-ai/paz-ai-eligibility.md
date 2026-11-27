---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You are not located in a country subject to U.S. government embargo or designated as a "terrorist supporting" country
  entity_types:
  - text: If representing an organization, you have authority to bind that organization to these Terms
    type: business
  minimum_age:
    text: You are at least 16 years of age or the minimum age of digital consent in your jurisdiction, whichever is higher
    value: '16'
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
name: Paz Ai
provenance_date: '2026-11-10'
provider_name: Paz Ai
provider_slug: paz-ai
slug: paz-ai-eligibility
source_date: '2026-11-10'
source_filename: paz-ai-eligibility.yml
source_heading: Eligibility
source_page: https://www.paz.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Paz Ai\naid: paz-ai\nurl: https://www.paz.ai/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You are not located in a country subject to U.S. government embargo or designated as a \"terrorist supporting\"\n    country\nentity_types:\n- type: business\n  text: If representing an organization, you have authority to bind that organization to these Terms\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: You are at least 16 years of age or the minimum age of digital consent in your jurisdiction,\
  \ whichever is\n    higher\n"
source_yaml_url: https://artifacts.apis.io/paz-ai/eligibility/paz-ai-eligibility.yml
stated_fields:
- countries
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from Paz Ai's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Commerce
- E-Commerce
- Agentic Commerce
- Product Feeds
- AI Search
- Retail
---
