---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: the Subscriber identified on the applicable Order Form
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Competitive product building
    text: use, access, or otherwise exploit the Services to build or support, and/or assist a third party in building or supporting, products or services competitive to the Services
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
name: UptimeHealth
provenance_date: '2026-11-10'
provider_name: UptimeHealth
provider_slug: uptimehealth
slug: uptimehealth-eligibility
source_date: '2026-11-10'
source_filename: uptimehealth-eligibility.yml
source_heading: Eligibility
source_page: https://www.uptimehealth.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: UptimeHealth\naid: uptimehealth\nurl: https://www.uptimehealth.com/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: the Subscriber identified on the applicable Order Form\nrestricted_uses:\n- summary: Competitive product building\n  text: use, access, or otherwise exploit the Services to build or support, and/or assist a third party in building\n    or supporting, products or services competitive to the Services\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value:\
  \ null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/uptimehealth/eligibility/uptimehealth-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from UptimeHealth's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- Dental
- Medical Equipment
- Compliance
- Facilities Management
- Equipment Maintenance
---
