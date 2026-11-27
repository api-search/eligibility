---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: unless you are using the Services in your personal capacity, in which case such terms refer to you as an individual.
    type: individual
  minimum_age:
    text: you are at least 18 years old
    value: '18'
  restricted_uses:
  - summary: No sensitive data
    text: 'you are prohibited from uploading or submitting to the Services, any information or data that is includes any of the following: any personal health information, personal medical information, personal financial information of any nature, or any sensitive personal information'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: We may, in our sole discretion, reject, change, suspend and/or terminate your Account.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Coefficient
provenance_date: '2026-11-09'
provider_name: Coefficient
provider_slug: coefficient
slug: coefficient-eligibility
source_date: '2026-11-09'
source_filename: coefficient-eligibility.yml
source_heading: Eligibility
source_page: https://coefficient.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Coefficient\naid: coefficient\nurl: https://coefficient.io/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: unless you are using the Services in your personal capacity, in which case such terms refer to you as an\n    individual.\nrestricted_uses:\n- summary: No sensitive data\n  text: 'you are prohibited from uploading or submitting to the Services, any information or data that is includes\n    any of the following: any personal health information, personal medical information, personal financial information\n    of any nature,\
  \ or any sensitive personal information'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: We may, in our sole discretion, reject, change, suspend and/or terminate your Account.\nminimum_age:\n  value: '18'\n  text: you are at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/coefficient/eligibility/coefficient-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Coefficient's own page on 2026-11-09.
synthetic: false
tags:
- Data Connectors
- AI Dashboards
- Spreadsheet Integration
- Revenue Operations
- Finance
- Marketing
---
