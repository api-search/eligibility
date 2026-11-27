---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: YOU MAY NOT ACCESS OR USE THE SERVICES OR ACCEPT THESE TERMS IF YOU ARE NOT AT LEAST 18 YEARS OLD.
    value: '18'
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
name: Cocoon
provenance_date: '2026-11-09'
provider_name: Cocoon
provider_slug: cocoon
slug: cocoon-eligibility
source_date: '2026-11-09'
source_filename: cocoon-eligibility.yml
source_heading: Eligibility
source_page: https://www.cocoon.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cocoon\naid: cocoon\nurl: https://www.cocoon.com/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: YOU MAY NOT ACCESS OR USE THE SERVICES OR ACCEPT THESE TERMS IF YOU ARE NOT AT LEAST 18 YEARS OLD.\n"
source_yaml_url: https://artifacts.apis.io/cocoon/eligibility/cocoon-eligibility.yml
stated_fields:
- minimum_age
summary_line: 1 quoted statement, read from Cocoon's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Human Resources
- Leave Management
- Compliance
- Payroll
- HRIS
- Employee Benefits
- EmployeeLeave
- Software-as-a-Service
---
