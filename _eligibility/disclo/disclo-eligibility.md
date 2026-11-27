---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: for your personal, noncommercial use only
    type: individual
  - text: We offer employers a cloud platform and other services to help them manage workplace disability accommodations for their employees, including you.
    type: business
  minimum_age:
    text: The Services are not intended for use by persons under the age of 18.
    value: '18'
  restricted_uses:
  - summary: Commercial solicitation
    text: (k) use the Services for any commercial solicitation purposes
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
name: Disclo
provenance_date: '2026-11-09'
provider_name: Disclo
provider_slug: disclo
slug: disclo-eligibility
source_date: '2026-11-09'
source_filename: disclo-eligibility.yml
source_heading: Eligibility
source_page: https://www.disclo.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Disclo\naid: disclo\nurl: https://www.disclo.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: for your personal, noncommercial use only\n- type: business\n  text: We offer employers a cloud platform and other services to help them manage workplace disability accommodations\n    for their employees, including you.\nrestricted_uses:\n- summary: Commercial solicitation\n  text: (k) use the Services for any commercial solicitation purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: '18'\n  text: The Services are not intended for use by persons under the age of 18.\n"
source_yaml_url: https://artifacts.apis.io/disclo/eligibility/disclo-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Disclo's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Workplace Accommodations
- Disability
- Human Resources
- ADA Compliance
- FMLA
- Leave Management
- Medical Certification
- HRIS Integration
- Health Data
---
