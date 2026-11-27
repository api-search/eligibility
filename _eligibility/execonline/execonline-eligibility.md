---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must register for a personal account on the Platform (a “User Account”) by providing an email address for your User Account
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No disclosure of personally identifiable info
    text: you agree not to disclose information about individuals that may be deemed personally identifiable under applicable laws, including but not limited to, personal health or financial information or personal information about children under the age of 13.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Additional information may be required to confirm your identity, and different or additional information may be required depending on your use of the Platform or enrollment in Programs.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: ExecOnline
provenance_date: '2026-11-09'
provider_name: ExecOnline
provider_slug: execonline
slug: execonline-eligibility
source_date: '2026-11-09'
source_filename: execonline-eligibility.yml
source_heading: Eligibility
source_page: https://www.execonline.com/terms-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ExecOnline\naid: execonline\nurl: https://www.execonline.com/terms-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must register for a personal account on the Platform (a “User Account”) by providing an email address\n    for your User Account\nrestricted_uses:\n- summary: No disclosure of personally identifiable info\n  text: you agree not to disclose information about individuals that may be deemed personally identifiable under\n    applicable laws, including but not limited to, personal health or financial information\
  \ or personal information\n    about children under the age of 13.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Additional information may be required to confirm your identity, and different or additional information\n    may be required depending on your use of the Platform or enrollment in Programs.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/execonline/eligibility/execonline-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from ExecOnline's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Education
- Leadership Development
- Executive Education
- Corporate Learning
- Learning and Development
- EdTech
- Coaching
- Talent Development
- Human Resources
- Software-as-a-Service
---
