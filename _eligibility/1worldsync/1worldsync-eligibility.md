---
api_specs:
- filename: 1worldsync-fetchproduct-api-openapi.yml
  format: yaml
  label: 1WorldSync FetchProduct API
  slug: 1worldsync-fetchproduct-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/1worldsync/openapi/1worldsync-fetchproduct-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: 1WorldSync controls and operates the Sites from offices located in the United States and makes no representations or warranties that the information, products, or services contained on the Sites are appropriate for use or access in other locations.
  minimum_age:
    text: you represent and warrant that you are at least the age of majority in the jurisdiction in which you reside
    value: null
  restricted_uses:
  - summary: Export-controlled software
    text: 'no software from this Sites may be downloaded, exported, or re-exported: (a) into (or to a national or resident of) any country to which the United States has embargoed goods'
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
name: 1WorldSync
provenance_date: '2026-11-09'
provider_name: 1WorldSync
provider_slug: 1worldsync
slug: 1worldsync-eligibility
source_date: '2026-11-09'
source_filename: 1worldsync-eligibility.yml
source_heading: Eligibility
source_page: https://1worldsync.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: 1WorldSync\naid: 1worldsync\nurl: https://1worldsync.com/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: 1WorldSync controls and operates the Sites from offices located in the United States and makes no representations\n    or warranties that the information, products, or services contained on the Sites are appropriate for use or\n    access in other locations.\nentity_types: []\nrestricted_uses:\n- summary: Export-controlled software\n  text: 'no software from this Sites may be downloaded, exported, or re-exported: (a) into (or to a national or\n\
  \    resident of) any country to which the United States has embargoed goods'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: you represent and warrant that you are at least the age of majority in the jurisdiction in which you reside\n"
source_yaml_url: https://artifacts.apis.io/1worldsync/eligibility/1worldsync-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from 1WorldSync's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Product Content
- GDSN
- Data Syndication
- Master Data
- Digital Shelf
- Product Information Management
- Consumer Packaged Goods
- Retail
- GS1
---
