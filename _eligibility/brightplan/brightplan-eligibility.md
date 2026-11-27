---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: regulated investment advice ("Advisory Services") is made available solely in the United States of America to U.S. residents and citizens
  entity_types:
  - text: you must be 18 or older, or of the legal age in your jurisdiction to form a binding contract if that age is greater than 18 years of age, to register as a user of Service.
    type: individual
  minimum_age:
    text: you must be 18 or older, or of the legal age in your jurisdiction to form a binding contract if that age is greater than 18 years of age
    value: '18'
  restricted_uses:
  - summary: Registration void where prohibited
    text: Registration for the Service is void where prohibited by applicable law and the right to access the Service is revoked in such jurisdictions.
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
name: BrightPlan
provenance_date: '2026-11-09'
provider_name: BrightPlan
provider_slug: brightplan
slug: brightplan-eligibility
source_date: '2026-11-09'
source_filename: brightplan-eligibility.yml
source_heading: Eligibility
source_page: https://www.brightplan.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BrightPlan\naid: brightplan\nurl: https://www.brightplan.com/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: regulated investment advice (\"Advisory Services\") is made available solely in the United States of America\n    to U.S. residents and citizens\nentity_types:\n- type: individual\n  text: you must be 18 or older, or of the legal age in your jurisdiction to form a binding contract if that age\n    is greater than 18 years of age, to register as a user of Service.\nrestricted_uses:\n- summary: Registration void where prohibited\n  text: Registration for\
  \ the Service is void where prohibited by applicable law and the right to access the Service\n    is revoked in such jurisdictions.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you must be 18 or older, or of the legal age in your jurisdiction to form a binding contract if that age\n    is greater than 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/brightplan/eligibility/brightplan-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from BrightPlan's own page on 2026-11-09.
synthetic: false
tags:
- Financial Wellness
- Financial Planning
- Employee Benefits
- Human Resources
- Wealth Management
- Financial Services
- Retirement
- Investment-Advice
- Company
---
