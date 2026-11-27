---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: any Company that has accepted the Agreement via an Order Form incorporating this Agreement by reference
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No fraud or illegal activity
    text: Customer, or any Authorized User, is using the Provider Technology for fraudulent or illegal activities
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
name: Concourse
provenance_date: '2026-11-09'
provider_name: Concourse
provider_slug: concourse
slug: concourse-eligibility
source_date: '2026-11-09'
source_filename: concourse-eligibility.yml
source_heading: Eligibility
source_page: https://www.concourse.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Concourse\naid: concourse\nurl: https://www.concourse.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: any Company that has accepted the Agreement via an Order Form incorporating this Agreement by reference\nrestricted_uses:\n- summary: No fraud or illegal activity\n  text: Customer, or any Authorized User, is using the Provider Technology for fraudulent or illegal activities\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/concourse/eligibility/concourse-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Concourse's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- AI Agents
- Corporate Finance
- Financial Reporting
- FP&A
- Accounting
- Analytics
---
