---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You represent that you are (i) at least thirteen (13) years old; (ii) of legal age to form a binding contract
    type: individual
  minimum_age:
    text: You represent that you are (i) at least thirteen (13) years old
    value: '13'
  restricted_uses:
  - summary: No prohibited or unlawful use
    text: you agree not to use Odeko Properties for any purpose that is prohibited by this Agreement or by applicable law.
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
name: Odeko
provenance_date: '2026-11-10'
provider_name: Odeko
provider_slug: odeko
slug: odeko-eligibility
source_date: '2026-11-10'
source_filename: odeko-eligibility.yml
source_heading: Eligibility
source_page: https://www.odeko.com/terms-of-use.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Odeko\naid: odeko\nurl: https://www.odeko.com/terms-of-use.html\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You represent that you are (i) at least thirteen (13) years old; (ii) of legal age to form a binding contract\nrestricted_uses:\n- summary: No prohibited or unlawful use\n  text: you agree not to use Odeko Properties for any purpose that is prohibited by this Agreement or by applicable\n    law.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You represent\
  \ that you are (i) at least thirteen (13) years old\n"
source_yaml_url: https://artifacts.apis.io/odeko/eligibility/odeko-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Odeko's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Food
- Cafe
- Coffee
- Supply Chain
- Logistics
- Commerce
- Shopify
---
