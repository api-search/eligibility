---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Employers who seek Candidates for employment through posting jobs
    type: business
  - text: Candidates who are being referred to an Employer’s job post through a Connector.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unauthorized or illegal use
    text: Promote, endorse or further illegal activities.
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
name: Liftoff
provenance_date: '2026-11-09'
provider_name: Liftoff
provider_slug: liftoff
slug: liftoff-eligibility
source_date: '2026-11-09'
source_filename: liftoff-eligibility.yml
source_heading: Eligibility
source_page: https://www.onliftoff.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Liftoff\naid: liftoff\nurl: https://www.onliftoff.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Employers who seek Candidates for employment through posting jobs\n- type: individual\n  text: Candidates who are being referred to an Employer’s job post through a Connector.\nrestricted_uses:\n- summary: Unauthorized or illegal use\n  text: Promote, endorse or further illegal activities.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/liftoff/eligibility/liftoff-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Liftoff's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Hiring
- Recruiting
- Talent
- Human Resources
- Professional Networking
- Referrals
- Software-as-a-Service
---
