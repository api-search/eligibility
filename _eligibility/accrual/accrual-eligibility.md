---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: or the organization that you represent in agreeing to the Agreement.
    type: business
  minimum_age:
    text: any access to, or use of, the Services by anyone who is a minor (which is under the age of 18 in most jurisdictions) in any applicable jurisdiction is strictly prohibited
    value: '18'
  restricted_uses:
  - summary: Tax advice reliance
    text: The Services are not intended to provide specific tax advice to any individual or business.
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
name: Accrual
provenance_date: '2026-11-09'
provider_name: Accrual
provider_slug: accrual
slug: accrual-eligibility
source_date: '2026-11-09'
source_filename: accrual-eligibility.yml
source_heading: Eligibility
source_page: https://auth.accrual.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Accrual\naid: accrual\nurl: https://auth.accrual.com/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: or the organization that you represent in agreeing to the Agreement.\nrestricted_uses:\n- summary: Tax advice reliance\n  text: The Services are not intended to provide specific tax advice to any individual or business.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: any access to, or use of, the Services by anyone who is a minor (which is under the age\
  \ of 18 in most jurisdictions)\n    in any applicable jurisdiction is strictly prohibited\n"
source_yaml_url: https://artifacts.apis.io/accrual/eligibility/accrual-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Accrual's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Accounting
- Tax
- Assurance
- Accounting Software
- Artificial Intelligence
- Software-as-a-Service
---
