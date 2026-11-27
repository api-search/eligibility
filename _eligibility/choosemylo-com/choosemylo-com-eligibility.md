---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You are thirteen (13) years of age or older
    value: '13'
  restricted_uses:
  - summary: AI Tool access restrictions
    text: 'You may not: (a) access Mylo’s AI Tools other than through an authorized AI Platform'
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
name: Mylo
provenance_date: '2026-11-09'
provider_name: Mylo
provider_slug: choosemylo-com
slug: choosemylo-com-eligibility
source_date: '2026-11-09'
source_filename: choosemylo-com-eligibility.yml
source_heading: Eligibility
source_page: https://choosemylo.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Mylo\naid: choosemylo-com\nurl: https://choosemylo.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: AI Tool access restrictions\n  text: 'You may not: (a) access Mylo’s AI Tools other than through an authorized AI Platform'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You are thirteen (13) years of age or older\n"
source_yaml_url: https://artifacts.apis.io/choosemylo-com/eligibility/choosemylo-com-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Mylo's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Insurance
- Insurtech
- Insurance Brokerage
- Small Business
- Quotes
- MCP
---
