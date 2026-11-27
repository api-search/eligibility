---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: any businesses (herein “Customer”) with which it has an active service agreement
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful or deceptive use
    text: use, or allow the use of, the Platform for any unfair or deceptive practices or in contravention of any federal, state, local, foreign, or other applicable law
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
name: Spoiler Alert
provenance_date: '2026-11-10'
provider_name: Spoiler Alert
provider_slug: spoiler-alert
slug: spoiler-alert-eligibility
source_date: '2026-11-10'
source_filename: spoiler-alert-eligibility.yml
source_heading: Eligibility
source_page: https://www.spoileralert.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Spoiler Alert\naid: spoiler-alert\nurl: https://www.spoileralert.com/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: any businesses (herein “Customer”) with which it has an active service agreement\nrestricted_uses:\n- summary: Unlawful or deceptive use\n  text: use, or allow the use of, the Platform for any unfair or deceptive practices or in contravention of any\n    federal, state, local, foreign, or other applicable law\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/spoiler-alert/eligibility/spoiler-alert-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Spoiler Alert's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Consumer Packaged Goods
- Food Waste
- Inventory
- Supply Chain
- Retail
- Marketplace
- Sustainability
---
