---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be 16 or over to open an account.
    type: individual
  - text: Enterprise is set by a written agreement with your organisation
    type: business
  minimum_age:
    text: You must be 16 or over to open an account.
    value: '16'
  restricted_uses:
  - summary: Presenting content as own work or medical advice
    text: present our stories or Ask answers as your own work, or as medical advice
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
name: AgingResearch.News
provenance_date: '2026-11-09'
provider_name: AgingResearch.News
provider_slug: agingresearch-news
slug: agingresearch-news-eligibility
source_date: '2026-11-09'
source_filename: agingresearch-news-eligibility.yml
source_heading: Eligibility
source_page: https://agingresearch.news/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AgingResearch.News\naid: agingresearch-news\nurl: https://agingresearch.news/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be 16 or over to open an account.\n- type: business\n  text: Enterprise is set by a written agreement with your organisation\nrestricted_uses:\n- summary: Presenting content as own work or medical advice\n  text: present our stories or Ask answers as your own work, or as medical advice\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n\
  \  text: You must be 16 or over to open an account.\n"
source_yaml_url: https://artifacts.apis.io/agingresearch-news/eligibility/agingresearch-news-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from AgingResearch.News's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Aging
- Longevity
- Artificial Intelligence
- Research
- News
---
