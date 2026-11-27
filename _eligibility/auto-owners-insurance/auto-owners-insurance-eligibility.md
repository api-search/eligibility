---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: This site is controlled, operated and administered by us from offices within the United States of America and for the purpose of servicing our policyholders and assisting independent insurance agents in the marketing and promoting of our products and services solely in states in which we write business.
  entity_types:
  - text: the person accessing this site
    type: individual
  - text: including a business or other organization
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unauthorized access or interruption
    text: 'You agree not to attempt to: a) interrupt the operation of any site; b) gain unauthorized access to our computers or computer codes'
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
name: Auto-Owners Insurance
provenance_date: '2026-11-09'
provider_name: Auto-Owners Insurance
provider_slug: auto-owners-insurance
slug: auto-owners-insurance-eligibility
source_date: '2026-11-09'
source_filename: auto-owners-insurance-eligibility.yml
source_heading: Eligibility
source_page: https://www.auto-owners.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Auto-Owners Insurance\naid: auto-owners-insurance\nurl: https://www.auto-owners.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: This site is controlled, operated and administered by us from offices within the United States of America\n    and for the purpose of servicing our policyholders and assisting independent insurance agents in the marketing\n    and promoting of our products and services solely in states in which we write business.\nentity_types:\n- type: individual\n  text: the person accessing this site\n- type: business\n  text: including a business\
  \ or other organization\nrestricted_uses:\n- summary: Unauthorized access or interruption\n  text: 'You agree not to attempt to: a) interrupt the operation of any site; b) gain unauthorized access to our\n    computers or computer codes'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/auto-owners-insurance/eligibility/auto-owners-insurance-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from Auto-Owners Insurance's own page on 2026-11-09.
synthetic: false
tags:
- Insurance
- Auto Insurance
- Home Insurance
- Life Insurance
- Business Insurance
- Mutual Insurance
- Independent Agents
---
