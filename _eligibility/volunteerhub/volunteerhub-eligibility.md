---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Illegal use
    text: You agree (i) not to use the Software or Services for any illegal purposes
  - summary: Protected health information
    text: upload and/or store any files or other data containing information that is considered to be Protected Health Information (PHI)
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
name: VolunteerHub
provenance_date: '2026-11-10'
provider_name: VolunteerHub
provider_slug: volunteerhub
slug: volunteerhub-eligibility
source_date: '2026-11-10'
source_filename: volunteerhub-eligibility.yml
source_heading: Eligibility
source_page: https://volunteerhub.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: VolunteerHub\naid: volunteerhub\nurl: https://volunteerhub.com/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Illegal use\n  text: You agree (i) not to use the Software or Services for any illegal purposes\n- summary: Protected health information\n  text: upload and/or store any files or other data containing information that is considered to be Protected Health\n    Information (PHI)\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/volunteerhub/eligibility/volunteerhub-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 2 quoted statements, read from VolunteerHub's own page on 2026-11-10.
synthetic: false
tags:
- Volunteer Management
- Non-Profit
- Scheduling
- Recruiting
- Platform
---
