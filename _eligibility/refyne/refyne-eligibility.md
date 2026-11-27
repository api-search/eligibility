---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Employee/Gig Worker/Pensioners users
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No unlawful, misleading or fraudulent use
    text: Shall not do anything that is unlawful, misleading, discriminatory or fraudulent.
  verification:
    approval_required: true
    kyb: null
    kyc: true
    text: subject to due diligence/approval by the NBFC
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Refyne
provenance_date: '2026-11-10'
provider_name: Refyne
provider_slug: refyne
slug: refyne-eligibility
source_date: '2026-11-10'
source_filename: refyne-eligibility.yml
source_heading: Eligibility
source_page: https://www.refyne.co.in/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Refyne\naid: refyne\nurl: https://www.refyne.co.in/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Employee/Gig Worker/Pensioners users\nrestricted_uses:\n- summary: No unlawful, misleading or fraudulent use\n  text: Shall not do anything that is unlawful, misleading, discriminatory or fraudulent.\nverification:\n  kyc: true\n  kyb: null\n  approval_required: true\n  text: subject to due diligence/approval by the NBFC\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/refyne/eligibility/refyne-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from Refyne's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fintech
- Earned Wage Access
- Financial Wellness
- Salary On-Demand
- Payroll
- Lending
- India
---
