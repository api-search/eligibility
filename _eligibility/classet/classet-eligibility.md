---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Services are intended for users who are at least 18 years old.
    type: individual
  minimum_age:
    text: The Services are intended for users who are at least 18 years old. Persons under the age of 18 are not permitted to use or register for the Services.
    value: '18'
  restricted_uses:
  - summary: Prohibited activities list
    text: Impersonate another individual or submit fraudulent job applications.
  - summary: Discriminatory job content
    text: Post or promote discriminatory, hateful, or harassing content in job listings or application materials.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You may be required to register to use the Services.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Classet
provenance_date: '2026-11-09'
provider_name: Classet
provider_slug: classet
slug: classet-eligibility
source_date: '2026-11-09'
source_filename: classet-eligibility.yml
source_heading: Eligibility
source_page: https://www.classet.ai/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Classet\naid: classet\nurl: https://www.classet.ai/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Services are intended for users who are at least 18 years old.\nrestricted_uses:\n- summary: Prohibited activities list\n  text: Impersonate another individual or submit fraudulent job applications.\n- summary: Discriminatory job content\n  text: Post or promote discriminatory, hateful, or harassing content in job listings or application materials.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n\
  \  text: You may be required to register to use the Services.\nminimum_age:\n  value: '18'\n  text: The Services are intended for users who are at least 18 years old. Persons under the age of 18 are not permitted\n    to use or register for the Services.\n"
source_yaml_url: https://artifacts.apis.io/classet/eligibility/classet-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Classet's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Recruiting
- Applicant Tracking
- Automation
- Enterprise
---
