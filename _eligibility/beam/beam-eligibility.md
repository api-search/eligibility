---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: you are not a minor in the jurisdiction in which you reside
    value: null
  restricted_uses:
  - summary: Illegal or unauthorized purposes
    text: you will not use the Site for any illegal or unauthorized purpose
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
name: Beam
provenance_date: '2026-11-09'
provider_name: Beam
provider_slug: beam
slug: beam-eligibility
source_date: '2026-11-09'
source_filename: beam-eligibility.yml
source_heading: Eligibility
source_page: https://www.trybeam.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Beam\naid: beam\nurl: https://www.trybeam.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Illegal or unauthorized purposes\n  text: you will not use the Site for any illegal or unauthorized purpose\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: you are not a minor in the jurisdiction in which you reside\n"
source_yaml_url: https://artifacts.apis.io/beam/eligibility/beam-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Beam's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Payments
- Construction
- Fintech
- Invoicing
- Job Costing
- Expense Management
- Contractors
- Cash Management
- Software-as-a-Service
---
