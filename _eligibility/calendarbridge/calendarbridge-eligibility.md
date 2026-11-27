---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You represent and warrant that you are an individual of legal age to form a binding contract
    type: individual
  minimum_age:
    text: we do not knowingly collect or solicit personal information from anyone under the age of 16.
    value: '16'
  restricted_uses:
  - summary: Unlawful use prohibited
    text: If your use of the Services is prohibited by applicable laws, then you aren’t authorized to use the Services.
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
name: CalendarBridge
provenance_date: '2026-11-09'
provider_name: CalendarBridge
provider_slug: calendarbridge
slug: calendarbridge-eligibility
source_date: '2026-11-09'
source_filename: calendarbridge-eligibility.yml
source_heading: Eligibility
source_page: https://calendarbridge.com/terms-and-privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CalendarBridge\naid: calendarbridge\nurl: https://calendarbridge.com/terms-and-privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You represent and warrant that you are an individual of legal age to form a binding contract\nrestricted_uses:\n- summary: Unlawful use prohibited\n  text: If your use of the Services is prohibited by applicable laws, then you aren’t authorized to use the Services.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: we do not knowingly\
  \ collect or solicit personal information from anyone under the age of 16.\n"
source_yaml_url: https://artifacts.apis.io/calendarbridge/eligibility/calendarbridge-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from CalendarBridge's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Calendar
- Scheduling
- Integration
---
