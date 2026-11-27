---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Service is intended for use by individuals who are at least 18 years of age.
    type: individual
  - text: These Terms apply to all users of the Service, including but not limited to home care agencies ("Agency Customers")
    type: business
  minimum_age:
    text: The Service is intended for use by individuals who are at least 18 years of age.
    value: '18'
  restricted_uses:
  - summary: Discrimination prohibited
    text: (g) use the Service to discriminate against any individual in violation of applicable law;
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
name: Mochacare
provenance_date: '2026-11-10'
provider_name: Mochacare
provider_slug: mochacare
slug: mochacare-eligibility
source_date: '2026-11-10'
source_filename: mochacare-eligibility.yml
source_heading: Eligibility
source_page: https://www.mochacare.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Mochacare\naid: mochacare\nurl: https://www.mochacare.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Service is intended for use by individuals who are at least 18 years of age.\n- type: business\n  text: These Terms apply to all users of the Service, including but not limited to home care agencies (\"Agency\n    Customers\")\nrestricted_uses:\n- summary: Discrimination prohibited\n  text: (g) use the Service to discriminate against any individual in violation of applicable law;\nverification:\n  kyc: null\n  kyb: null\n\
  \  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Service is intended for use by individuals who are at least 18 years of age.\n"
source_yaml_url: https://artifacts.apis.io/mochacare/eligibility/mochacare-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Mochacare's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Home Care
- Healthcare
- Care Agencies
- Staffing
- Scheduling
- Applicant Tracking
- AI Agents
- Virtual Assistants
- Y Combinator
---
