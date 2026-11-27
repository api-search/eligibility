---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You are over the age of majority
    value: null
  restricted_uses:
  - summary: Educational use only
    text: The Services are designed for use by educators and parents/legal guardians in Educational Institutions.
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
name: Showbie
provenance_date: '2026-11-10'
provider_name: Showbie
provider_slug: showbie
slug: showbie-eligibility
source_date: '2026-11-10'
source_filename: showbie-eligibility.yml
source_heading: Eligibility
source_page: https://www.showbie.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Showbie\naid: showbie\nurl: https://www.showbie.com/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Educational use only\n  text: The Services are designed for use by educators and parents/legal guardians in Educational Institutions.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: You are over the age of majority\n"
source_yaml_url: https://artifacts.apis.io/showbie/eligibility/showbie-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Showbie's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Education
- EdTech
- K-12
- Learning Platform
- iPad
- Classroom
---
