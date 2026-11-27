---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: the company or person that Accepts the Agreement as set forth herein and its Affiliates (collectively “Customer”)
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export restrictions
    text: Each Party agrees not to export or re-export any such materials or information to any destination or entity prohibited or restricted under US law
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: CREXi may refuse to register or may cancel passwords that it deems inappropriate.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: CREXi
provenance_date: '2026-11-09'
provider_name: CREXi
provider_slug: crexi
slug: crexi-eligibility
source_date: '2026-11-09'
source_filename: crexi-eligibility.yml
source_heading: Eligibility
source_page: https://www.crexi.com/msa
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CREXi\naid: crexi\nurl: https://www.crexi.com/msa\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: the company or person that Accepts the Agreement as set forth herein and its Affiliates (collectively “Customer”)\nrestricted_uses:\n- summary: Export restrictions\n  text: Each Party agrees not to export or re-export any such materials or information to any destination or entity\n    prohibited or restricted under US law\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: CREXi may refuse to register or may cancel\
  \ passwords that it deems inappropriate.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/crexi/eligibility/crexi-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from CREXi's own page on 2026-11-09.
synthetic: false
tags:
- Real Estate
- Commercial Real Estate
- Marketplace
- Property Data
- Listings
- Auctions
- Market Intelligence
- Data Syndication
- RESO
- Company
---
