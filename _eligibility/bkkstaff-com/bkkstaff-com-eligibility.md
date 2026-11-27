---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: BKK Staff provides a hiring assistant for employers.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Acceptable use limits
    text: You may not use BKK Staff to post fraudulent jobs, collect personal data for purposes other than hiring, or discriminate against candidates based on protected characteristics.
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
name: BKK Staff
provenance_date: '2026-11-09'
provider_name: BKK Staff
provider_slug: bkkstaff-com
slug: bkkstaff-com-eligibility
source_date: '2026-11-09'
source_filename: bkkstaff-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.bkkstaff.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BKK Staff\naid: bkkstaff-com\nurl: https://www.bkkstaff.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: BKK Staff provides a hiring assistant for employers.\nrestricted_uses:\n- summary: Acceptable use limits\n  text: You may not use BKK Staff to post fraudulent jobs, collect personal data for purposes other than hiring,\n    or discriminate against candidates based on protected characteristics.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/bkkstaff-com/eligibility/bkkstaff-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from BKK Staff's own page on 2026-11-09.
synthetic: false
tags:
- Hiring
- Staffing
- Small Business
- Automation
- Thailand
---
