---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: solely for Customer’s internal business purposes
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Recording calls requires customer consent notices
    text: Customer is solely responsible for complying with all applicable wiretapping and call recording laws.
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
name: Rapidfolio
provenance_date: '2026-11-10'
provider_name: Rapidfolio
provider_slug: rapidfolio
slug: rapidfolio-eligibility
source_date: '2026-11-10'
source_filename: rapidfolio-eligibility.yml
source_heading: Eligibility
source_page: https://rapidfolio.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Rapidfolio\naid: rapidfolio\nurl: https://rapidfolio.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: solely for Customer’s internal business purposes\nrestricted_uses:\n- summary: Recording calls requires customer consent notices\n  text: Customer is solely responsible for complying with all applicable wiretapping and call recording laws.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/rapidfolio/eligibility/rapidfolio-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Rapidfolio's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Financial Services
- Fintech
- Workflow Automation
- Artificial Intelligence
- Agents
- Compliance
- KYC
- Fraud Prevention
- Back Office
---
