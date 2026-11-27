---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Platform is intended for individual users or members (hereinafter “Members”, “Users”, “You”) affiliated to a specific organization.
    type: individual
  minimum_age:
    text: (1) at least 18 years of age, or (2) at least 13 years of age and have parental consent.
    value: '13'
  restricted_uses:
  - summary: Competitors barred
    text: (c) are not our competitor, or are not using our Website or Platform for reasons that are in competition with us;
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
name: MentorCloud
provenance_date: '2026-11-10'
provider_name: MentorCloud
provider_slug: mentorcloud
slug: mentorcloud-eligibility
source_date: '2026-11-10'
source_filename: mentorcloud-eligibility.yml
source_heading: Eligibility
source_page: https://mentorcloud.com/utility/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: MentorCloud\naid: mentorcloud\nurl: https://mentorcloud.com/utility/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Platform is intended for individual users or members (hereinafter “Members”, “Users”, “You”) affiliated\n    to a specific organization.\nrestricted_uses:\n- summary: Competitors barred\n  text: (c) are not our competitor, or are not using our Website or Platform for reasons that are in competition\n    with us;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: '13'\n  text: (1) at least 18 years of age, or (2) at least 13 years of age and have parental consent.\n"
source_yaml_url: https://artifacts.apis.io/mentorcloud/eligibility/mentorcloud-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from MentorCloud's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Mentoring
- Mentorship
- Talent Development
- Employee Engagement
- Learning and Development
- Human Resources
- Software-as-a-Service
- DEI
- Higher Education
---
