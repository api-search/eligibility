---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: YOU ARE AT LEAST 13 YEARS OLD
    value: '13'
  restricted_uses:
  - summary: Violations of law or harmful use
    text: Violates any law or regulation.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Your employer may share certain information about you with Brightside so that we can verify your eligibility, confirm your identity, and provide the Services to you.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Brightside
provenance_date: '2026-11-09'
provider_name: Brightside
provider_slug: brightside
slug: brightside-eligibility
source_date: '2026-11-09'
source_filename: brightside-eligibility.yml
source_heading: Eligibility
source_page: https://www.gobrightside.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Brightside\naid: brightside\nurl: https://www.gobrightside.com/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Violations of law or harmful use\n  text: Violates any law or regulation.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Your employer may share certain information about you with Brightside so that we can verify your eligibility,\n    confirm your identity, and provide the Services to you.\nminimum_age:\n  value: '13'\n  text: YOU ARE AT LEAST 13 YEARS OLD\n"
source_yaml_url: https://artifacts.apis.io/brightside/eligibility/brightside-eligibility.yml
stated_fields:
- restricted_uses
- verification
- minimum_age
summary_line: 3 quoted statements, read from Brightside's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Financial Wellness
- Employee Benefits
- Financial Services
- Personal Finance
- Fintech
- Financial Care
---
