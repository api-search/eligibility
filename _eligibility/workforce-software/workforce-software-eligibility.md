---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: All attendees must be 21 or older.
    value: '21'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: IDs will be required to pick up a badge on-site.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: WorkForce Software
provenance_date: '2026-11-10'
provider_name: WorkForce Software
provider_slug: workforce-software
slug: workforce-software-eligibility
source_date: '2026-11-10'
source_filename: workforce-software-eligibility.yml
source_heading: Eligibility
source_page: https://workforcesoftware.com/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: WorkForce Software\naid: workforce-software\nurl: https://workforcesoftware.com/terms-and-conditions/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: IDs will be required to pick up a badge on-site.\nminimum_age:\n  value: '21'\n  text: All attendees must be 21 or older.\n"
source_yaml_url: https://artifacts.apis.io/workforce-software/eligibility/workforce-software-eligibility.yml
stated_fields:
- verification
- minimum_age
summary_line: 2 quoted statements, read from WorkForce Software's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Workforce Management
- Time and Attendance
- Scheduling
- Absence Management
- Human Resources
- Enterprise Software
---
