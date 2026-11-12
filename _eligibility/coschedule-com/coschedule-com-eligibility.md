---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Use of the Site is prohibited in any jurisdiction having laws that would void the Agreement in whole or essential part or which makes accessing the Site illegal.
  entity_types:
  - text: User represents and warrants to CoSchedule that if User is an individual (i.e., not a corporation) User is at least 18 years of age.
    type: individual
  minimum_age:
    text: User represents and warrants to CoSchedule that if User is an individual (i.e., not a corporation) User is at least 18 years of age.
    value: '18'
  restricted_uses:
  - summary: Unlawful or prohibited purposes
    text: User shall not use the Site or any Content for any purpose that is unlawful or prohibited by this Agreement.
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
name: CoSchedule
provenance_date: '2026-11-09'
provider_name: CoSchedule
provider_slug: coschedule-com
slug: coschedule-com-eligibility
source_date: '2026-11-09'
source_filename: coschedule-com-eligibility.yml
source_heading: Eligibility
source_page: https://coschedule.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CoSchedule\naid: coschedule-com\nurl: https://coschedule.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Use of the Site is prohibited in any jurisdiction having laws that would void the Agreement in whole or\n    essential part or which makes accessing the Site illegal.\nentity_types:\n- type: individual\n  text: User represents and warrants to CoSchedule that if User is an individual (i.e., not a corporation) User\n    is at least 18 years of age.\nrestricted_uses:\n- summary: Unlawful or prohibited purposes\n  text: User shall not use the Site or any Content for any\
  \ purpose that is unlawful or prohibited by this Agreement.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: User represents and warrants to CoSchedule that if User is an individual (i.e., not a corporation) User\n    is at least 18 years of age.\n"
source_yaml_url: https://artifacts.apis.io/coschedule-com/eligibility/coschedule-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from CoSchedule's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Marketing
- Social Media Management
- Content Calendar
- Marketing Automation
- Scheduling
- MCP
---
