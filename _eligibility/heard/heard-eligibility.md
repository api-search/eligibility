---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: Persons who are less than 18 years of age
    value: '18'
  restricted_uses:
  - summary: No use with client PII/PHI in AI Features
    text: enter or use personally identifiable information or protected health information of any client or customer of Client into or with any AI Feature
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
name: Heard
provenance_date: '2026-11-09'
provider_name: Heard
provider_slug: heard
slug: heard-eligibility
source_date: '2026-11-09'
source_filename: heard-eligibility.yml
source_heading: Eligibility
source_page: https://www.joinheard.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Heard\naid: heard\nurl: https://www.joinheard.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: No use with client PII/PHI in AI Features\n  text: enter or use personally identifiable information or protected health information of any client or customer\n    of Client into or with any AI Feature\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Persons who are less than 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/heard/eligibility/heard-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Heard's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Bookkeeping
- Accounting
- Tax
- Payroll
- Banking
- Financial Services
- Therapists
- Private Practice
- Mental Health
---
