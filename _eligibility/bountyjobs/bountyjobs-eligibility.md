---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: If Employer accesses this Website from outside of the United States, it does so at its own risk and is responsible for compliance with the laws of its jurisdiction.
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: BountyJobs cannot and does not confirm that each Headhunter and Candidate is who they claim to be.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Bountyjobs
provenance_date: '2026-11-09'
provider_name: Bountyjobs
provider_slug: bountyjobs
slug: bountyjobs-eligibility
source_date: '2026-11-09'
source_filename: bountyjobs-eligibility.yml
source_heading: Eligibility
source_page: https://bountyjobs.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bountyjobs\naid: bountyjobs\nurl: https://bountyjobs.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: If Employer accesses this Website from outside of the United States, it does so at its own risk and is responsible\n    for compliance with the laws of its jurisdiction.\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: BountyJobs cannot and does not confirm that each Headhunter and Candidate is who they claim to be.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/bountyjobs/eligibility/bountyjobs-eligibility.yml
stated_fields:
- countries
- verification
summary_line: 2 quoted statements, read from Bountyjobs's own page on 2026-11-09.
synthetic: false
tags:
- Recruiting Marketplace
- Extended Workforce
- Vendor Management
- Staffing Platform
- Recruiter Network
---
