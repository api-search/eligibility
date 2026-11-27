---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Uteach users must be 18 years old or elder, or at least at the age that gives them the right to do business in the territory where they live or where they use this service.
    type: individual
  - text: If a user has subscribed to Uteach services on behalf of an employer, then the account holder must be the employer.
    type: business
  minimum_age:
    text: Uteach users must be 18 years old or elder, or at least at the age that gives them the right to do business in the territory where they live or where they use this service.
    value: '18'
  restricted_uses:
  - summary: Illegal activities or malicious files
    text: It is forbidden to use Uteach to carry out illegal activities or transfer malicious files.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: To complete the registration process, you must provide a legal/real name, a valid email address, and any other information necessary for the registration process.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Uteach
provenance_date: '2026-11-10'
provider_name: Uteach
provider_slug: uteach-inc
slug: uteach-inc-eligibility
source_date: '2026-11-10'
source_filename: uteach-inc-eligibility.yml
source_heading: Eligibility
source_page: https://uteach.io/pages/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Uteach\naid: uteach-inc\nurl: https://uteach.io/pages/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Uteach users must be 18 years old or elder, or at least at the age that gives them the right to do business\n    in the territory where they live or where they use this service.\n- type: business\n  text: If a user has subscribed to Uteach services on behalf of an employer, then the account holder must be the\n    employer.\nrestricted_uses:\n- summary: Illegal activities or malicious files\n  text: It is forbidden\
  \ to use Uteach to carry out illegal activities or transfer malicious files.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: To complete the registration process, you must provide a legal/real name, a valid email address, and any\n    other information necessary for the registration process.\nminimum_age:\n  value: '18'\n  text: Uteach users must be 18 years old or elder, or at least at the age that gives them the right to do business\n    in the territory where they live or where they use this service.\n"
source_yaml_url: https://artifacts.apis.io/uteach-inc/eligibility/uteach-inc-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Uteach's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Education
- E-Learning
- LMS
- Online Courses
- Employee Training
- Coaching
- EdTech
---
