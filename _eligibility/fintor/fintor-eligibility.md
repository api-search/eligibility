---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If You are using the Service on behalf of another entity (such as your employer), You must have the authority to accept these Terms on their behalf.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Lending decisions require human review
    text: You are responsible for maintaining appropriate human oversight of AI Agent actions and reviewing Output before making lending decisions.
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
name: Fintor
provenance_date: '2026-11-09'
provider_name: Fintor
provider_slug: fintor
slug: fintor-eligibility
source_date: '2026-11-09'
source_filename: fintor-eligibility.yml
source_heading: Eligibility
source_page: https://www.fintor.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Fintor\naid: fintor\nurl: https://www.fintor.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If You are using the Service on behalf of another entity (such as your employer), You must have the authority\n    to accept these Terms on their behalf.\nrestricted_uses:\n- summary: Lending decisions require human review\n  text: You are responsible for maintaining appropriate human oversight of AI Agent actions and reviewing Output\n    before making lending decisions.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/fintor/eligibility/fintor-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Fintor's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Mortgage
- Lending
- Financial Services
- Artificial Intelligence
- AI Agents
- Automation
- Loan Origination
- Fintech
---
