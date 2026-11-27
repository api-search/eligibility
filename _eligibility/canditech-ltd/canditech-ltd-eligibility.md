---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years of age or older to use the Platform
    type: individual
  - text: Employer means any individual or entity who engaged with us or used the Platform to perform its Candidate screening or similar processes.
    type: business
  minimum_age:
    text: You must be at least 18 years of age or older to use the Platform
    value: '18'
  restricted_uses:
  - summary: Lawful use only
    text: You represent and warrant that you will use the Platform for legal and lawful purposes at all times
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
name: Canditech
provenance_date: '2026-11-09'
provider_name: Canditech
provider_slug: canditech-ltd
slug: canditech-ltd-eligibility
source_date: '2026-11-09'
source_filename: canditech-ltd-eligibility.yml
source_heading: Eligibility
source_page: https://system.canditech.io/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Canditech\naid: canditech-ltd\nurl: https://system.canditech.io/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years of age or older to use the Platform\n- type: business\n  text: Employer means any individual or entity who engaged with us or used the Platform to perform its Candidate\n    screening or similar processes.\nrestricted_uses:\n- summary: Lawful use only\n  text: You represent and warrant that you will use the Platform for legal and lawful purposes at all times\nverification:\n  kyc:\
  \ null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years of age or older to use the Platform\n"
source_yaml_url: https://artifacts.apis.io/canditech-ltd/eligibility/canditech-ltd-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Canditech's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Recruiting
- Hiring
- Skills Assessment
- Talent Assessment
- Pre-Employment Testing
- Job Simulation
- HR Technology
- ATS Integration
---
