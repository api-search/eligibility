---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Site is provided for users in the United States.
  minimum_age:
    text: This Site is offered and available to users who are 18 years of age or older
    value: '18'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Qwick may condition provision of an Account on results of background check, entity confirmation or similar verification.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Qwick
provenance_date: '2026-11-10'
provider_name: Qwick
provider_slug: qwick
slug: qwick-eligibility
source_date: '2026-11-10'
source_filename: qwick-eligibility.yml
source_heading: Eligibility
source_page: https://www.qwick.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Qwick\naid: qwick\nurl: https://www.qwick.com/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Site is provided for users in the United States.\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Qwick may condition provision of an Account on results of background check, entity confirmation or similar\n    verification.\nminimum_age:\n  value: '18'\n  text: This Site is offered and available to users who are 18 years of age or older\n"
source_yaml_url: https://artifacts.apis.io/qwick/eligibility/qwick-eligibility.yml
stated_fields:
- countries
- verification
- minimum_age
summary_line: 3 quoted statements, read from Qwick's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Marketplace
- Hospitality
- Staffing
- Workforce Management
- Gig Economy
- Payroll
- Scheduling
- On-Demand Labor
---
