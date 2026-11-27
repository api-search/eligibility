---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: an employee of a customer who has ordered access to the RightRev Site or Subscription Services through an order form
    type: business
  minimum_age:
    text: Persons who are not of the age of majority are not eligible to use the Site
    value: age of majority
  restricted_uses:
  - summary: Noncommercial use of Services absent separate agreement
    text: the Services may be used solely for your personal, informational, noncommercial purposes
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
name: Rightrev
provenance_date: '2026-11-10'
provider_name: Rightrev
provider_slug: rightrev
slug: rightrev-eligibility
source_date: '2026-11-10'
source_filename: rightrev-eligibility.yml
source_heading: Eligibility
source_page: https://www.rightrev.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Rightrev\naid: rightrev\nurl: https://www.rightrev.com/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: an employee of a customer who has ordered access to the RightRev Site or Subscription Services through an\n    order form\nrestricted_uses:\n- summary: Noncommercial use of Services absent separate agreement\n  text: the Services may be used solely for your personal, informational, noncommercial purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: age of majority\n\
  \  text: Persons who are not of the age of majority are not eligible to use the Site\n"
source_yaml_url: https://artifacts.apis.io/rightrev/eligibility/rightrev-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Rightrev's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Revenue Recognition
- Accounting
- Finance
- Billing
- ASC 606
- IFRS 15
- Revenue
- SaaS Metrics
---
