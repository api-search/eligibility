---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: If you are under 13 years of age, you are not authorized to use the Service, with or without registering.
    value: '13'
  restricted_uses:
  - summary: Competitors barred without permission
    text: No employee, independent contractor, agent, or affiliate of any competing company is permitted to view, access, or use any portion of the Service without express written permission from Branching Minds.
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
name: Branching Minds
provenance_date: '2026-11-09'
provider_name: Branching Minds
provider_slug: branching-minds
slug: branching-minds-eligibility
source_date: '2026-11-09'
source_filename: branching-minds-eligibility.yml
source_heading: Eligibility
source_page: https://www.branchingminds.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Branching Minds\naid: branching-minds\nurl: https://www.branchingminds.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Competitors barred without permission\n  text: No employee, independent contractor, agent, or affiliate of any competing company is permitted to view,\n    access, or use any portion of the Service without express written permission from Branching Minds.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: If you are under 13 years of\
  \ age, you are not authorized to use the Service, with or without registering.\n"
source_yaml_url: https://artifacts.apis.io/branching-minds/eligibility/branching-minds-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Branching Minds's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Education
- EdTech
- K-12
- MTSS
- RTI
- Student Data
- Intervention
- SIS Integration
---
