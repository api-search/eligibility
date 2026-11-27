---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Moz offers businesses and individuals access to resources for search engine optimization
    type: individual
  - text: Moz offers businesses and individuals access to resources for search engine optimization
    type: business
  minimum_age:
    text: with minimum ages of 13 years old for Users and 18 years old for Subscribers
    value: 13 for Users; 18 for Subscribers
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
name: Moz
provenance_date: '2026-11-10'
provider_name: Moz
provider_slug: moz
slug: moz-eligibility
source_date: '2026-11-10'
source_filename: moz-eligibility.yml
source_heading: Eligibility
source_page: https://moz.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Moz\naid: moz\nurl: https://moz.com/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Moz offers businesses and individuals access to resources for search engine optimization\n- type: business\n  text: Moz offers businesses and individuals access to resources for search engine optimization\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: 13 for Users; 18 for Subscribers\n  text: with minimum ages of 13 years old for Users and 18 years old for Subscribers\n"
source_yaml_url: https://artifacts.apis.io/moz/eligibility/moz-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from Moz's own page on 2026-11-10.
synthetic: false
tags:
- SEO
- Search
- Marketing
- Analytics
- Keywords
- Backlinks
- Local Marketing
- Domain Authority
- Link Index
- JSON-RPC
- MCP
- Company
---
