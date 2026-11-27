---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No unauthorized practice of law
    text: Customer will not use the Service, Eve AI or Output in any manner that constitutes the unauthorized practice of law
  - summary: Agentic features need attorney approval for legal filings
    text: Customer will not enable or permit an Agentic Feature to take any action having legal effect in a Matter, including filing, serving, executing, submitting, or transmitting any document to a court, tribunal, arbitrator, government authority, opposing party, or client, without prior review and approval by a licensed attorney
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
name: Eve
provenance_date: '2026-11-09'
provider_name: Eve
provider_slug: eve
slug: eve-eligibility
source_date: '2026-11-09'
source_filename: eve-eligibility.yml
source_heading: Eligibility
source_page: https://www.eve.legal/eve-enterprise-terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Eve\naid: eve\nurl: https://www.eve.legal/eve-enterprise-terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: No unauthorized practice of law\n  text: Customer will not use the Service, Eve AI or Output in any manner that constitutes the unauthorized practice\n    of law\n- summary: Agentic features need attorney approval for legal filings\n  text: Customer will not enable or permit an Agentic Feature to take any action having legal effect in a Matter,\n    including filing, serving, executing, submitting, or\
  \ transmitting any document to a court, tribunal, arbitrator,\n    government authority, opposing party, or client, without prior review and approval by a licensed attorney\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/eve/eligibility/eve-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 2 quoted statements, read from Eve's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Legal
- Legal AI
- Legal Tech
- Personal Injury
- Case Management
- Artificial Intelligence
- Document Review
- Software-as-a-Service
---
