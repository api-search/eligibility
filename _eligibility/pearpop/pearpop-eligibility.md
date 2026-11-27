---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old and able to enter into contracts in order to use Peari.
    type: individual
  minimum_age:
    text: You must be at least 18 years old and able to enter into contracts in order to use Peari.
    value: '18'
  restricted_uses:
  - summary: Export restrictions
    text: You may not use Peari or export Content in violation of United States export laws, regulations, or restrictions.
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
name: PearPop
provenance_date: '2026-11-10'
provider_name: PearPop
provider_slug: pearpop
slug: pearpop-eligibility
source_date: '2026-11-10'
source_filename: pearpop-eligibility.yml
source_heading: Eligibility
source_page: https://pearpop.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: PearPop\naid: pearpop\nurl: https://pearpop.ai/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old and able to enter into contracts in order to use Peari.\nrestricted_uses:\n- summary: Export restrictions\n  text: You may not use Peari or export Content in violation of United States export laws, regulations, or restrictions.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and able to enter into\
  \ contracts in order to use Peari.\n"
source_yaml_url: https://artifacts.apis.io/pearpop/eligibility/pearpop-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from PearPop's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Creator Economy
- Influencer Marketing
- Social Media
- Marketing
- Marketplace
- Talent Management
- Artificial Intelligence
---
