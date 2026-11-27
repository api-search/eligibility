---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: To create and use a student account, you must be at least 16 years old.
    type: individual
  - text: To create and use an individual account, you must be at least 18 years old .
    type: individual
  - text: To create an Employer Account you must either associate yourself with a current Handshake Employer Partner (“Employer Partner”) and be approved by that employer or create a new Employer Account.
    type: business
  minimum_age:
    text: To create and use a student account, you must be at least 16 years old.
    value: '16'
  restricted_uses:
  - summary: Handshake data not for analytics or monetization
    text: You shall only use student data to provide the employer services to the student and not use, sell, or disclose Handshake Data for any purposes including data analytics, data monetization, advertising, marketing or any other purpose even if such Handshake Data is aggregated or de-identiﬁed.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: To create an Employer Account you must either associate yourself with a current Handshake Employer Partner (“Employer Partner”) and be approved by that employer or create a new Employer Account.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Handshake
provenance_date: '2026-11-09'
provider_name: Handshake
provider_slug: handshake
slug: handshake-eligibility
source_date: '2026-11-09'
source_filename: handshake-eligibility.yml
source_heading: Eligibility
source_page: https://joinhandshake.com/legal/tos/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Handshake\naid: handshake\nurl: https://joinhandshake.com/legal/tos/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: To create and use a student account, you must be at least 16 years old.\n- type: individual\n  text: To create and use an individual account, you must be at least 18 years old .\n- type: business\n  text: To create an Employer Account you must either associate yourself with a current Handshake Employer Partner\n    (“Employer Partner”) and be approved by that employer or create a new Employer Account.\nrestricted_uses:\n\
  - summary: Handshake data not for analytics or monetization\n  text: You shall only use student data to provide the employer services to the student and not use, sell, or disclose\n    Handshake Data for any purposes including data analytics, data monetization, advertising, marketing or any other\n    purpose even if such Handshake Data is aggregated or de-identiﬁed.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: To create an Employer Account you must either associate yourself with a current Handshake Employer Partner\n    (“Employer Partner”) and be approved by that employer or create a new Employer Account.\nminimum_age:\n  value: '16'\n  text: To create and use a student account, you must be at least 16 years old.\n"
source_yaml_url: https://artifacts.apis.io/handshake/eligibility/handshake-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Handshake's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Human Resources
- Careers
- Recruiting
- Higher Education
- Talent
- Students
- Job
---
