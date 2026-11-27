---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 'If you are an Employer using the Crew app or other Services, these arbitration procedures apply to you:'
    type: business
  - text: 'If you are an individual End User of the Crew app or other Services, this arbitration provision applies to you:'
    type: individual
  minimum_age:
    text: By creating an account, you agree that you are at least 18 years of age.
    value: '18'
  restricted_uses:
  - summary: No tracking or spying on users
    text: Don’t use the Services to track, monitor, or spy on other users or employees.
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
name: Crew
provenance_date: '2026-11-09'
provider_name: Crew
provider_slug: crew
slug: crew-eligibility
source_date: '2026-11-09'
source_filename: crew-eligibility.yml
source_heading: Eligibility
source_page: https://www.crewapp.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Crew\naid: crew\nurl: https://www.crewapp.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: 'If you are an Employer using the Crew app or other Services, these arbitration procedures apply to you:'\n- type: individual\n  text: 'If you are an individual End User of the Crew app or other Services, this arbitration provision applies\n    to you:'\nrestricted_uses:\n- summary: No tracking or spying on users\n  text: Don’t use the Services to track, monitor, or spy on other users or employees.\nverification:\n  kyc: null\n\
  \  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: By creating an account, you agree that you are at least 18 years of age.\n"
source_yaml_url: https://artifacts.apis.io/crew/eligibility/crew-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Crew's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Application
- Workforce Management
- Frontline
- Communications
- Scheduling
- Task Management
- Employee Engagement
---
