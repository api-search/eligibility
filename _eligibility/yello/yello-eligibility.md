---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: either (a) a business organization, or (b) an individual user
    type: business
  - text: either (a) a business organization, or (b) an individual user
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No health, financial or SSN data
    text: Customer hereby acknowledges and agrees that it is not authorized to submit health data, financial data, or social security information into the System or Services
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
name: Yello
provenance_date: '2026-11-10'
provider_name: Yello
provider_slug: yello
slug: yello-eligibility
source_date: '2026-11-10'
source_filename: yello-eligibility.yml
source_heading: Eligibility
source_page: https://yello.co/msa/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Yello\naid: yello\nurl: https://yello.co/msa/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: either (a) a business organization, or (b) an individual user\n- type: individual\n  text: either (a) a business organization, or (b) an individual user\nrestricted_uses:\n- summary: No health, financial or SSN data\n  text: Customer hereby acknowledges and agrees that it is not authorized to submit health data, financial data,\n    or social security information into the System or Services\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/yello/eligibility/yello-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Yello's own page on 2026-11-10.
synthetic: false
tags:
- Talent Acquisition
- Recruiting
- Human Resources
- Campus Recruiting
- Applicant Tracking
- Recruitment CRM
- Interview Scheduling
- Job
- MCP
- Government
---
