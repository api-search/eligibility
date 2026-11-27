---
api_specs:
- filename: curai-partner-api-openapi.yml
  format: yaml
  label: Curai Partner API
  slug: curai-partner-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/curai/openapi/curai-partner-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Telemedicine Consultations are not available in every state, nor are they available at all times
  entity_types:
  - text: To use the Services, you must be at least 18 years old.
    type: individual
  minimum_age:
    text: To use the Services, you must be at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: Accessing healthcare for others
    text: Utilizing your account to gain access to healthcare for anyone other than yourself
  - summary: Doctor shopping
    text: ‘Doctor Shopping’ — visiting acute care repeatedly to make duplicate requests of different Curai Health doctors for the same problem
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You certify that you are physically located in the state you select in the Services as your current location at the time of your receipt of the Care Services.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Curai
provenance_date: '2026-11-09'
provider_name: Curai
provider_slug: curai
slug: curai-eligibility
source_date: '2026-11-09'
source_filename: curai-eligibility.yml
source_heading: Eligibility
source_page: https://www.curaihealth.com/legal#tc
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Curai\naid: curai\nurl: https://www.curaihealth.com/legal#tc\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: Telemedicine Consultations are not available in every state, nor are they available at all times\nentity_types:\n- type: individual\n  text: To use the Services, you must be at least 18 years old.\nrestricted_uses:\n- summary: Accessing healthcare for others\n  text: Utilizing your account to gain access to healthcare for anyone other than yourself\n- summary: Doctor shopping\n  text: ‘Doctor Shopping’ — visiting acute care repeatedly to make duplicate requests\
  \ of different Curai Health\n    doctors for the same problem\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You certify that you are physically located in the state you select in the Services as your current location\n    at the time of your receipt of the Care Services.\nminimum_age:\n  value: '18'\n  text: To use the Services, you must be at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/curai/eligibility/curai-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Curai's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Health
- Healthcare
- Telehealth
- Primary Care
- Digital Health
- Patient Engagement
- Partner API
- SDK
- Artificial Intelligence
---
