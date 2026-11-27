---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: This Section 15 applies if Customer is a governmental or public entity, including the U.S. federal government or any agency or instrument of any federal, state, or local governmental entity.
    type: government
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No protected health information
    text: Customer agrees that it will not upload protected health information
  - summary: No payment cardholder data
    text: will not upload into the Provider Technology or the Services any credit, debit, or other payment cardholder information
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
name: EverTrue
provenance_date: '2026-11-09'
provider_name: EverTrue
provider_slug: evertrue
slug: evertrue-eligibility
source_date: '2026-11-09'
source_filename: evertrue-eligibility.yml
source_heading: Eligibility
source_page: https://www.evertrue.com/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: EverTrue\naid: evertrue\nurl: https://www.evertrue.com/terms-and-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: government\n  text: This Section 15 applies if Customer is a governmental or public entity, including the U.S. federal government\n    or any agency or instrument of any federal, state, or local governmental entity.\nrestricted_uses:\n- summary: No protected health information\n  text: Customer agrees that it will not upload protected health information\n- summary: No payment cardholder data\n  text: will not\
  \ upload into the Provider Technology or the Services any credit, debit, or other payment cardholder\n    information\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/evertrue/eligibility/evertrue-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from EverTrue's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Ai Apps
- Fundraising
- Non-Profit
- Donor Management
- Higher Education
- Advancement
- Prospect Research
- Stewardship
---
