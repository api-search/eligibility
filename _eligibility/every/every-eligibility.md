---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: (c) you are a legal resident of the United States
  minimum_age:
    text: you are at least 18 years old
    value: '18'
  restricted_uses:
  - summary: No consumer or personal use
    text: Any use of or access to the Services for consumer or non-commercial purposes, or by any individual who is not your employee, contractor, agent, or other individual permitted to use your Every Account on your behalf is strictly prohibited
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
name: Every
provenance_date: '2026-11-09'
provider_name: Every
provider_slug: every
slug: every-eligibility
source_date: '2026-11-09'
source_filename: every-eligibility.yml
source_heading: Eligibility
source_page: https://www.every.io/legal/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Every\naid: every\nurl: https://www.every.io/legal/tos\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: (c) you are a legal resident of the United States\nentity_types: []\nrestricted_uses:\n- summary: No consumer or personal use\n  text: Any use of or access to the Services for consumer or non-commercial purposes, or by any individual who is\n    not your employee, contractor, agent, or other individual permitted to use your Every Account on your behalf\n    is strictly prohibited\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text:\
  \ null\nminimum_age:\n  value: '18'\n  text: you are at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/every/eligibility/every-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Every's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Banking
- Payroll
- Human Resources
- Bookkeeping
- Accounting
- Tax
- Treasury
- Incorporation
- Startups
---
