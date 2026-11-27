---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: User - an individual adult who has registered on the App by creating a Profile
    type: individual
  minimum_age:
    text: User - an individual adult who has registered on the App by creating a Profile
    value: null
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: We do not check the data provided in the process of registration for accuracy.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Aspire Learning
provenance_date: '2026-11-09'
provider_name: Aspire Learning
provider_slug: aspirelearning-app
slug: aspirelearning-app-eligibility
source_date: '2026-11-09'
source_filename: aspirelearning-app-eligibility.yml
source_heading: Eligibility
source_page: https://aspirelearning.app/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Aspire Learning\naid: aspirelearning-app\nurl: https://aspirelearning.app/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: User - an individual adult who has registered on the App by creating a Profile\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: We do not check the data provided in the process of registration for accuracy.\nminimum_age:\n  value: null\n  text: User - an individual adult who has registered on the App by creating a Profile\n"
source_yaml_url: https://artifacts.apis.io/aspirelearning-app/eligibility/aspirelearning-app-eligibility.yml
stated_fields:
- entity_types
- verification
- minimum_age
summary_line: 3 quoted statements, read from Aspire Learning's own page on 2026-11-09.
synthetic: false
tags:
- Education
- Learning
- Software-as-a-Service
- Platform
- Students
---
