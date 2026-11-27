---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: companies and other entities (each, a “ Customer ”) may use the software services
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Government end use restrictions
    text: If Customer (or any of its customers) is an agency, department, or other entity of any government, the use, duplication, reproduction, release, modification, disclosure, or transfer of the Services, or any related documentation of any kind, including technical data, software, and manuals, is restricted by the terms of this Agreement.
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
name: Parspec
provenance_date: '2026-11-10'
provider_name: Parspec
provider_slug: parspec
slug: parspec-eligibility
source_date: '2026-11-10'
source_filename: parspec-eligibility.yml
source_heading: Eligibility
source_page: https://intercom.help/parspec/en/articles/10206451-terms-of-service-distributors
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Parspec\naid: parspec\nurl: https://intercom.help/parspec/en/articles/10206451-terms-of-service-distributors\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: companies and other entities (each, a “ Customer ”) may use the software services\nrestricted_uses:\n- summary: Government end use restrictions\n  text: If Customer (or any of its customers) is an agency, department, or other entity of any government, the use,\n    duplication, reproduction, release, modification, disclosure, or transfer of the Services, or any related documentation\n\
  \    of any kind, including technical data, software, and manuals, is restricted by the terms of this Agreement.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/parspec/eligibility/parspec-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Parspec's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Software-as-a-Service
- Construction
- MEP
- Electrical
- Distribution
- Quoting
- Submittals
- Project Management
- AEC
---
