---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If Customer or its Users are an agency, department, or other entity of the United States Government, the use, duplication, reproduction, release, modification, disclosure, or transfer of the Revenue Products is restricted
    type: government
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Automated decisions affecting individuals
    text: (I) make automated decisions that may have a detrimental impact on individual rights without appropriate human supervision
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
name: RingDNA
provenance_date: '2026-11-10'
provider_name: RingDNA
provider_slug: ringdna
slug: ringdna-eligibility
source_date: '2026-11-10'
source_filename: ringdna-eligibility.yml
source_heading: Eligibility
source_page: https://www.revenue.io/msa
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: RingDNA\naid: ringdna\nurl: https://www.revenue.io/msa\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: government\n  text: If Customer or its Users are an agency, department, or other entity of the United States Government, the\n    use, duplication, reproduction, release, modification, disclosure, or transfer of the Revenue Products is restricted\nrestricted_uses:\n- summary: Automated decisions affecting individuals\n  text: (I) make automated decisions that may have a detrimental impact on individual rights without appropriate\n    human supervision\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/ringdna/eligibility/ringdna-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from RingDNA's own page on 2026-11-10.
synthetic: false
tags:
- Sales Engagement
- Conversation Intelligence
- Sales Dialing
- Call Recording
- Revenue Orchestration
- CRM Integration
- Salesforce
- AI Coaching
- Sales Automation
---
