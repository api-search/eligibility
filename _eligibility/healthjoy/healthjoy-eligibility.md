---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: HealthJoy is based in the United States; as such, we provide the Service for use only by persons located in the United States.
  entity_types:
  - text: The Service is only offered and available to users who are at least eighteen (18) years of age or older.
    type: individual
  minimum_age:
    text: The Service is only offered and available to users who are at least eighteen (18) years of age or older.
    value: '18'
  restricted_uses:
  - summary: Personal use only for virtual consults
    text: HealthJoy is for personal use in accordance with local, state, and federal law only and may not be used for commercial purposes.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Accounts may only be set up by the individual that is the subject of the account, and who is of the age of majority.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: HealthJoy
provenance_date: '2026-11-09'
provider_name: HealthJoy
provider_slug: healthjoy
slug: healthjoy-eligibility
source_date: '2026-11-09'
source_filename: healthjoy-eligibility.yml
source_heading: Eligibility
source_page: https://www.healthjoy.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: HealthJoy\naid: healthjoy\nurl: https://www.healthjoy.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: HealthJoy is based in the United States; as such, we provide the Service for use only by persons located\n    in the United States.\nentity_types:\n- type: individual\n  text: The Service is only offered and available to users who are at least eighteen (18) years of age or older.\nrestricted_uses:\n- summary: Personal use only for virtual consults\n  text: HealthJoy is for personal use in accordance with local, state, and federal law only\
  \ and may not be used\n    for commercial purposes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Accounts may only be set up by the individual that is the subject of the account, and who is of the age\n    of majority.\nminimum_age:\n  value: '18'\n  text: The Service is only offered and available to users who are at least eighteen (18) years of age or older.\n"
source_yaml_url: https://artifacts.apis.io/healthjoy/eligibility/healthjoy-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from HealthJoy's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Health
- Healthcare
- Employee Benefits
- Benefits Administration
- Health Insurance
- Healthcare Navigation
- Human Resources
- Insurance
- Artificial Intelligence
- HIPAA
- Cost Containment
---
