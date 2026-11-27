---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: RSS, podcast, Markdown and JSON API endpoints are provided for personal and non-commercial use
    type: individual
  - text: Commercial use requires written permission.
    type: business
  minimum_age:
    text: null
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
name: Basis Desk
provenance_date: '2026-11-09'
provider_name: Basis Desk
provider_slug: basisdesk-news
slug: basisdesk-news-eligibility
source_date: '2026-11-09'
source_filename: basisdesk-news-eligibility.yml
source_heading: Eligibility
source_page: https://basisdesk.news/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Basis Desk\naid: basisdesk-news\nurl: https://basisdesk.news/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: RSS, podcast, Markdown and JSON API endpoints are provided for personal and non-commercial use\n- type: business\n  text: Commercial use requires written permission.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/basisdesk-news/eligibility/basisdesk-news-eligibility.yml
stated_fields:
- entity_types
summary_line: 2 quoted statements, read from Basis Desk's own page on 2026-11-09.
synthetic: false
tags:
- Cryptocurrency
- News
- Artificial Intelligence
- Media
- Data
- Finance
---
