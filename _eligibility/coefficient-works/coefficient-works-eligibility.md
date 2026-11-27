---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: the business, organization or entity with which you are associated and for which you act
    type: business
  minimum_age:
    text: you are at least 18 years old
    value: '18'
  restricted_uses:
  - summary: No sensitive data uploads
    text: 'you are prohibited from uploading or submitting to the Services, any information or data that is includes any of the following: any personal health information'
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
name: Coefficient Works
provenance_date: '2026-11-09'
provider_name: Coefficient Works
provider_slug: coefficient-works
slug: coefficient-works-eligibility
source_date: '2026-11-09'
source_filename: coefficient-works-eligibility.yml
source_heading: Eligibility
source_page: https://coefficient.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Coefficient Works\naid: coefficient-works\nurl: https://coefficient.io/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: the business, organization or entity with which you are associated and for which you act\nrestricted_uses:\n- summary: No sensitive data uploads\n  text: 'you are prohibited from uploading or submitting to the Services, any information or data that is includes\n    any of the following: any personal health information'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: '18'\n  text: you are at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/coefficient-works/eligibility/coefficient-works-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Coefficient Works's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Spreadsheets
- Google Sheets
- Microsoft Excel
- Data Integration
- No-Code
- Business Intelligence
- Reporting
- Revenue Operations
- Software-as-a-Service
---
