---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: YOU MAY NOT ACCESS OR USE THE SERVICES OR ENTER INTO THIS AGREEMENT IF YOU ARE NOT AT LEAST 18 YEARS OLD.
    value: '18'
  restricted_uses:
  - summary: Not for time-critical or mission-critical functions
    text: Customer acknowledges and agrees that the Company Platform will not be used, and are not licensed for use, in connection with any of Customer’s time-critical or mission-critical functions.
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
name: Wiselayer
provenance_date: '2026-11-10'
provider_name: Wiselayer
provider_slug: wiselayer
slug: wiselayer-eligibility
source_date: '2026-11-10'
source_filename: wiselayer-eligibility.yml
source_heading: Eligibility
source_page: https://www.wiselayer.com/terms-and-conditions-for-customers
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Wiselayer\naid: wiselayer\nurl: https://www.wiselayer.com/terms-and-conditions-for-customers\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Not for time-critical or mission-critical functions\n  text: Customer acknowledges and agrees that the Company Platform will not be used, and are not licensed for use,\n    in connection with any of Customer’s time-critical or mission-critical functions.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: YOU MAY NOT ACCESS\
  \ OR USE THE SERVICES OR ENTER INTO THIS AGREEMENT IF YOU ARE NOT AT LEAST 18 YEARS OLD.\n"
source_yaml_url: https://artifacts.apis.io/wiselayer/eligibility/wiselayer-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Wiselayer's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Accounting
- Finance
- Automation
- Agents
- Accruals
- Accounting Automation
- Fintech
---
