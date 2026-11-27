---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: the individual or the corporation, society, partnership, or other legal entity identified as such on the applicable Order Form
    type: business
  - text: an individual with the legal capacity to enter into a contract, or the sole proprietorship of such an individual
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Illegal activity
    text: use the System for illegal activities or in violation of any application law, rule or regulation
  - summary: Harm to minors
    text: use the Products or System to harm minors in any way
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
name: Kindsight
provenance_date: '2026-11-09'
provider_name: Kindsight
provider_slug: kindsight
slug: kindsight-eligibility
source_date: '2026-11-09'
source_filename: kindsight-eligibility.yml
source_heading: Eligibility
source_page: https://kindsight.io/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Kindsight\naid: kindsight\nurl: https://kindsight.io/terms-and-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: the individual or the corporation, society, partnership, or other legal entity identified as such on the\n    applicable Order Form\n- type: individual\n  text: an individual with the legal capacity to enter into a contract, or the sole proprietorship of such an individual\nrestricted_uses:\n- summary: Illegal activity\n  text: use the System for illegal activities or in violation of any application\
  \ law, rule or regulation\n- summary: Harm to minors\n  text: use the Products or System to harm minors in any way\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/kindsight/eligibility/kindsight-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from Kindsight's own page on 2026-11-09.
synthetic: false
tags:
- Fundraising
- Artificial Intelligence
- Non-Profit
- Data
- Platform
---
